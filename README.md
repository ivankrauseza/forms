# forms
## email validation
Source from ChatGPT  
    function validateEmail() {
    var email = document.getElementById("email").value;
    var regex = /^\S+@\S+\.\S+$/; // email validation regular expression
    if (!regex.test(email)) {
    alert("Please enter a valid email address");
    return false;
    }
    return true;
    }


## Credits / Resources
[Google Fonts - Jost](https://fonts.google.com/specimen/Jost)