# FormSanitize
/*

    if(isset($_POST["submitBtn"])){
        //$firstName = $_POST["firstName"];
        $firstName = sanitizeFormString($_POST["firstName"]); //sanitized version of the string
        echo $firstName;
        
    }

    function sanitizeFormString ($inputText){
        //remove HTML tags from any string
        $inputText = strip_tags($inputText);
        //remove spaces from text
        $inputText = str_replace(" ", "", $inputText); //replace any space with an empty string in $inputText
        //for people with spaces in their names e.g Al Mashauri
        //$inputText = trim($inputText); //removes spaces from before and after but not within the string
        
        //convert strings to lowercase
        $inputText = strtolower($inputText);
        //uppercase the first character of the string
        $inputText = ucfirst($inputText);
        return $inputText;
    }
*/
