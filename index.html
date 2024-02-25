<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Voice Website</title>
</head>
<body>
    <h1>Ask a Question</h1>
    <form id="questionForm">
        <label for="question">Ask your question:</label><br>
        <input type="text" id="question" name="question"><br>
        <button type="submit">Submit</button>
    </form>

    <div id="response"></div>

    <script>

document.getElementById("questionForm").addEventListener("submit", function(event) {
    event.preventDefault();
    var question = document.getElementById("question").value;

    var xhr = new XMLHttpRequest();
    xhr.onreadystatechange = function() {
        if (xhr.readyState === XMLHttpRequest.DONE) {
            if (xhr.status === 200) {
                document.getElementById("response").innerHTML = xhr.responseText;
            } else {
                console.error("Error:", xhr.status);
            }
        }
    };
    xhr.open("GET", "response.php?question=" + encodeURIComponent(question), true);
    xhr.send();
});



    </script>

<?php
// Define predefined responses
$responses = [
    "what is your name" => "I'm fine.",
    // Add more predefined questions and responses here
];

// Get the question from the query parameters
$question = $_GET['question'];

// Look up the response based on the question
$response = isset($responses[$question]) ? $responses[$question] : "Sorry, I don't understand that question.";

// Output the response
echo $response;
?>

</body>
</html>
