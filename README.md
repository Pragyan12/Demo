<!DOCTYPE html>
<html>
<head>
<title>!WelCome To Hello World!</title>
</head>
<body>
   <div id='content' ng-controller='LoginController'>
    <div class="container">
        <form class="form-signin" role="form" ng-submit="login()">
            <h3 class="form-signin-heading">Login Form</h3>
            <span><b>Username :</b>&nbsp; <input type=type="text" ng-model="username"
                class="form-control" ng-model="user.name" required> </span> </br>
            </br> <span><b>Password :</b>&nbsp;&nbsp; <input type=type="text" ng-model="password"
                class="form-control" ng-model="user.password" required> </span>
            <br><br>
            <button class="btn btn-lg btn-primary btn-block" type="submit">
                <b>Sign in</b>
            </button>
        </form>
    </div>
    <!-- /container -->
</div>
</body>
</html>
