<html>
<form action="http://example.com/company.php" method="get">
<fieldset>
<legend>
Account Information
</legend>
<label>Company Name:<br />
<input type="text" name="company"></label>
<br />
<label>Company Location: <br /><input type="text" name="location"></label><br />
<label>Username:<br /><input type="text" name="username" size="15" maxlength="25"></label><br />
<label>Password: <br /> <input type="password" name="password" size="15" maxlength="30"></label>
</fieldset>

<fieldset>
<legend>Position Information</legend>
<label>Position Title:<br /><input type="text" name="title" maxlength="30"></label><br />
<label>Vacation Time:<br /><input type="number" name="time"></label><br />
<label>Pay/hr:<br /><input type="number" name="price" min="0" value="0" step="any"></label><br />

</fieldset>
<input type="submit" value="submit" />

</form>
</html>
