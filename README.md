herefrom flask import Flask

app = Flask(__name__)

@app.route('/')
def home():
    return "Hello, Zero to Hero!"

if __name__ == '__main__':
    app.run()
