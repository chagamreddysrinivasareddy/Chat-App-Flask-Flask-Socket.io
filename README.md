# Chat-App-Flask-Flask-Socket.io
### Installation

 1. Clone the repository.
 2. Install all the required libraries by running the following command 

pip install Flask Flask-socketIo Flask-session eventlet

### Create a template

 create chat.html and index.html in template folder 

### Creating the Flask App and Configuring SocketIO

   app = Flask(__name__) initializes the Flask app.

   socketio = SocketIO(app, manage_session=False)

### Defining Routes and Views
 
   @app.route('/', methods=['GET', 'POST'])

### Running the App

   if __name__ == '__main__':
     socketio.run(app)

### Run
Execute the application by 

    python app.py
