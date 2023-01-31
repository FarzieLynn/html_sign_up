# html_sign_up
<!DOCTYPE html>
<html lang="en">
    <form>
        <h2 >Email</h2>
        <input type="text" name="Email" value="" placeholder="Put your email here...">
        <h2>Password</h2>
        <input type="text" name="Password" value="" placehoder="">
        <h2>Github Username</h2>
        <input type="text" name="Github Username" value="" placeholder="Input Github Username here...">
            <fieldset>
                <legend>Select a Plan:</legend>
                
                <div>
                    <input type="radio" id="Enterprise" name="drone" value="Enterprise"

                    checked>
                    <label for="Enterprise">Enterprise</label>
                </div>
                <div>
                    <input type="radio" id="Pro" name="drone" value="Pro"

                    checked>
                    <label for="Pro">Pro</label>
                </div>
                <div>
                    <input type="radio" id="Free" name="drone" value="Free"

                    checked>
                    <label for="Free">Free</label>
                </div>
            </fieldset>
                <div>
                    <input type="checkbox" id="Remember Me" name="Remember Me" checked>
                    <label for="Remember Me">Remember Me</label>
                </div>
                
    </form>
</html>
