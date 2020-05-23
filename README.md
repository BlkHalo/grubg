# grubg



Moved two classes out of dbModels.py file into their own file (post_dbModels.py)

Created a base class and modified the other two classes:
  - created new class named Post
  - renamed class User_Posts to class Topic
  - renamed class Post_Replies to class Reply

Added the imports [below] from dbModels.py to post_dbModels.py, but not sure if that is necessary:

#Database Table Models
from myproject import login_manager, db
from werkzeug.security import generate_password_hash,check_password_hash
from flask_login import UserMixin


Looked around the rest of the files in the repo and was not able to determine if the class name changes (Topic, Reply) would cause any issues. 


