<div class="container">
    <h1>User detail</h1>

    <form novalidate="novalidate" class="form-horizontal">
        <div class="control-group">
            <label class="control-label" for="inputFirstName">First name:</label>
            <div class="controls">
                <input type="text" id="inputFirstName" ng-model="user.firstName"/>
            </div>
        </div>
        <div class="control-group">
            <label class="control-label" for="inputLastName">Last name:</label>
            <div class="controls">
                <input type="text" id="inputLastName" ng-model="user.lastName"/>
            </div>
        </div>
        <div class="control-group">
            <div class="controls">
              <!-- user-detail.html: -->
                <a ng-click="cancel()" class="btn btn-small">cancel</a>
                <a ng-click="updateUser()" class="btn btn-small btn-primary">update user</a>

              <!-- user-creation.html: -->
                <a ng-click="createNewUser()" class="btn btn-small btn-primary">create new user</a>
            </div>
        </div>
    </form>
</div>
