(Postexmp.py)

from flask import *
app = Flask(__name__)
@app.route('/login',methods = ['POST'])
def login():
	uname=request.form['uname']
	passwrd=request.form['pass']
	if uname == "Debu" and passwrd=="google":
		return "Welcome %s" %uname,

	if name == 'main':
		app.run(debug=True)


(login.html)
<html>
<bod>
	<form action = "http://localhost:5000/login" method="post">
<table>
	<tr><td>Name</td>
		<td><input type="text" name="uname"></td></tr>
	<tr><td>Password</td>
		<td><input type="password" name="pass"></td></tr>
	<tr> <td><input type="submit" name="button">	
</table>
	</form>
</body>
</html>
