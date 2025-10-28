herefrom flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def home():
    return "Zero to Hero Study Planner is live! 🚀"

if __name__ == '__main__':
    app.run(host='0.0.0.0', port=8080)
