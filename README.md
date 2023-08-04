**Social Book**

The social media app project is designed to provide a seamless and engaging user experience. It empowers users to create and share their content through various types of posts, such as images, videos, and text. With the ability to follow and unfollow other users, individuals can build their social network and stay updated with the latest posts from those they are interested in. The app's personalized feed ensures that users receive relevant and tailored content, enhancing user engagement. Users can express their appreciation for posts by liking them, fostering a sense of community and interaction. Additionally, the option to download images facilitates content sharing beyond the app's boundaries. The user search feature allows for easy discovery of new accounts, encouraging connections with like-minded individuals. Overall, the app aims to deliver a dynamic and interactive platform for users to connect, share, and explore content in a user-friendly environment.

**Prerequisites**
1. Python: Django is a web framework built on Python, so you need to have Python installed on your system. Make sure you have Python 3.x installed since Django does not support Python 2.

2. Virtual Environment: It's a good practice to create a virtual environment for your Django project to keep dependencies isolated. You can use virtualenv or venv to create a virtual environment.

3. Django Installation: Once you have Python and a virtual environment set up, you'll need to install Django. You can do this using pip, the Python package manager, by running:

   pip install django

4. Code Editor or IDE: You'll need a code editor or an Integrated Development Environment (IDE) to write and manage your Django project's code. Popular choices include Visual Studio Code, PyCharm, or Sublime Text.

5. Basic Web Development Knowledge: While Django simplifies web development, having a fundamental understanding of HTML, CSS, and JavaScript can be beneficial for creating dynamic web pages.


**Getting Started**

1. Clone the Repository: Clone the project repository to your local machine using the following command:
   
   git clone https://github.com/shristid21/Social-Book.git

2. Create a Virtual Environment: Navigate into the cloned project directory and create a virtual environment (optional but recommended):
 
   cd Social-Book
   
   python -m venv venv

3. Activate the Virtual Environment: Activate the virtual environment to isolate your project dependencies:
   
   On Windows:
   
   venv\Scripts\activate

   On macOS and Linux:
   
   source venv/bin/activate
  
4. Install Dependencies: While inside the virtual environment, install the required project dependencies specified in the project's requirements.txt file using pip:
   
   pip install -r requirements.txt

5. Apply Migrations: Run the following command to apply database migrations:
    
   python manage.py migrate

6. Create a Superuser: This project has user authentication, create a superuser account using the following command:
    
   python manage.py createsuperuser
   
7. Run the Development Server: Start the development server to run the Django project:
    
   python manage.py runserver
  
8. Test the Project: Open your web browser and navigate to http://127.0.0.1:8000/ to see the running project.you can access the admin panel at http://127.0.0.1:8000/admin/.
