@{
    ViewData["Title"] = "Register";
}

<h2>Register</h2>

<form asp-action="Register" method="post">
    <div class="form-group">
        <label for="Email">Email</label>
        <input type="email" class="form-control" id="Email" name="Email" required />
    </div>
    <div class="form-group">
        <label for="Password">Password</label>
        <input type="password" class="form-control" id="Password" name="Password" required />
    </div>
    <div class="form-group">
        <label for="ConfirmPassword">Confirm Password</label>
        <input type="password" class="form-control" id="ConfirmPassword" name="ConfirmPassword" required />
    </div>
    <button type="submit" class="btn btn-primary">Register</button>
</form>