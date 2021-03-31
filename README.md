pip3 install -r requirements.txt

python3
from app import mongo
mongo.db.tasks.create_index([("task_description", "text"), ("task_description", "text")])