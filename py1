from flask import Flask, request, render_template

app = Flask(__name__)

@app.route('/', methods=['GET', 'POST'])
def home():
    if request.method == 'POST':
        # you can access the search query with request.form['search']
        search_query = request.form['search']
        return 'Thank You'
    return render_template('index.html')

if __name__ == '__main__':
    app.run(debug=True)
