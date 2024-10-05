<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>C++ Lessons</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            padding: 14px 20px;
            color: white;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
        }
        h2 {
            color: #4CAF50;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #333;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>C++ Programming Lessons</h1>
</header>

<nav>
    <a href="#intro">Introduction</a>
    <a href="#basics">Basic Concepts</a>
    <a href="#lessons">Lessons</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <section id="intro">
        <h2>Introduction</h2>
        <p>C++ is a powerful, high-level programming language that is widely used for system/software development, game development, and in performance-critical applications.</p>
    </section>

    <section id="basics">
        <h2>Basic Concepts</h2>
        <ul>
            <li><strong>Variables:</strong> Containers for storing data values.</li>
            <li><strong>Data Types:</strong> Common types include int, float, char, and string.</li>
            <li><strong>Control Structures:</strong> if-else, switch, loops (for, while).</li>
            <li><strong>Functions:</strong> Reusable blocks of code.</li>
        </ul>
    </section>

    <section id="lessons">
        <h2>Sample Lessons</h2>
        <h3>Lesson 1: Hello World</h3>
        <p>To create your first C++ program, you can use the following code:</p>
        <pre>
#include &lt;iostream&gt;
using namespace std;

int main() {
    cout &lt;&lt; "Hello, World!" &lt;&lt; endl;
    return 0;
}
        </pre>

        <h3>Lesson 2: Variables and Data Types</h3>
        <p>Learn how to declare variables and use different data types:</p>
        <pre>
#include &lt;iostream&gt;
using namespace std;

int main() {
    int age = 30;
    float height = 5.9;
    char initial = 'A';
    
    cout &lt;&lt; "Age: " &lt;&lt; age &lt;&lt; endl;
    cout &lt;&lt; "Height: " &lt;&lt; height &lt;&lt; endl;
    cout &lt;&lt; "Initial: " &lt;&lt; initial &lt;&lt; endl;
    return 0;
}
        </pre>
    </section>
</div>

<footer id="contact">
    <p>Contact us: email@example.com</p>
    <p>&copy; 2024 C++ Lessons</p>
</footer>

</body>
</html>
