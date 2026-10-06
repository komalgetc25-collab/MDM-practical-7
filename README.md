<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>FAQ Section</title>

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-gray-100">

    <div class="max-w-2xl mx-auto p-6">

        <h1 class="text-3xl font-bold text-center text-blue-600 mb-8">
            Frequently Asked Questions
        </h1>

        <!-- FAQ 1 -->
        <div class="bg-white rounded-lg shadow mb-4">

            <button class="question w-full text-left p-4 font-semibold text-gray-800">
                What is HTML?
            </button>

            <div class="answer hidden p-4 bg-blue-50 text-gray-600">
                HTML is used to create the structure of a web page.
            </div>

        </div>


        <!-- FAQ 2 -->
        <div class="bg-white rounded-lg shadow mb-4">

            <button class="question w-full text-left p-4 font-semibold text-gray-800">
                What is CSS?
            </button>

            <div class="answer hidden p-4 bg-blue-50 text-gray-600">
                CSS is used to style and design web pages.
            </div>

        </div>


        <!-- FAQ 3 -->
        <div class="bg-white rounded-lg shadow mb-4">

            <button class="question w-full text-left p-4 font-semibold text-gray-800">
                What is JavaScript?
            </button>

            <div class="answer hidden p-4 bg-blue-50 text-gray-600">
                JavaScript is used to make web pages interactive.
            </div>

        </div>


        <!-- FAQ 4 -->
        <div class="bg-white rounded-lg shadow mb-4">

            <button class="question w-full text-left p-4 font-semibold text-gray-800">
                Can I use this on GitHub?
            </button>

            <div class="answer hidden p-4 bg-blue-50 text-gray-600">
                Yes. Save the file as index.html and upload it to GitHub Pages.
            </div>

        </div>

    </div>


    <script>

        // Select all questions
        const questions = document.querySelectorAll(".question");

        // Add click event
        questions.forEach(function(question) {

            question.addEventListener("click", function() {

                // Find the answer
                const answer = question.nextElementSibling;

                // Show / hide answer
                answer.classList.toggle("hidden");

            });

        });

    </script>

</body>
</html>
