<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Store Application</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        .header, .footer {
            text-align: center;
            background-color: #2c3e50;
            color: #ecf0f1;
            padding: 20px;
            border-bottom: 5px solid #3498db;
        }
        .header img, .footer img {
            width: 70%;
            border-radius: 10px;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        h1, h2, h3 {
            color: #34495e;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
        }
        h1 {
            font-family: 'Arial Black', Gadget, sans-serif;
            font-size: 42px;
        }
        h2 {
            color: #3498db;
            font-size: 28px;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        h3 {
            color: #e67e22;
            font-weight: bold;
        }
        p {
            background-color: #ecf0f1;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        ul, ol {
            padding-left: 20px;
            line-height: 1.6;
        }
        ul li, ol li {
            margin-bottom: 10px;
        }
        .screenshot img {
            width: 100%;
            max-width: 800px;
            display: block;
            margin: 20px auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .button {
            display: inline-block;
            background-color: #e74c3c;
            color: #fff;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }
        .button:hover {
            background-color: #c0392b;
        }
        .centered {
            text-align: center;
        }
        .highlight {
            color: #e74c3c;
            font-weight: bold;
        }
        .img-gallery img {
            width: 100%;
            max-width: 300px;
            display: inline-block;
            margin: 10px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .footer {
            background-color: #2c3e50;
            padding: 20px;
        }
        .footer h2 {
            color: #e67e22;
        }
    </style>
</head>
<body>
    <!-- Add a Header with Background Image -->
    <div class="header">
        <img src="https://via.placeholder.com/1000x400.png?text=Book+Store+Project" alt="Book Store Banner">
    </div>

    <div class="container">
        <!-- Centered Heading with Custom Font -->
        <h1 class="centered">📚 Book Store Application (MERN Stack)</h1>

        <!-- Centered Subheading with Custom Styling -->
        <h3 class="centered">Explore, Manage, and Enjoy Books Like Never Before!</h3>

        <!-- Centered Introduction with Custom Background -->
        <p class="centered">A sophisticated and responsive online bookstore designed with the MERN stack for a seamless browsing and shopping experience.</p>

        <!-- Features Section with Custom Icons -->
        <h2>🌟 Key Features</h2>
        <ul>
            <li>📚 <strong>Book Management:</strong> Add, edit, and delete books with ease.</li>
            <li>🔐 <strong>User Authentication:</strong> Secure signup, login, and logout functionalities.</li>
            <li>🔍 <strong>Browse and Search:</strong> Discover books by categories, authors, or titles.</li>
            <li>🎁 <strong>Free Book Access:</strong> Access a curated selection of free books.</li>
            <li>📖 <strong>Courses:</strong> Enroll in and explore engaging book-related courses.</li>
            <li>📱 <strong>Responsive UI:</strong> Optimized for mobile and desktop devices.</li>
        </ul>

        <!-- Data Source Section with Custom Styling -->
        <h2>📂 Data Source</h2>
        <p>Data is aggregated from various book management APIs to provide a comprehensive and up-to-date library.</p>

        <!-- Technology Stack with Custom Styling -->
        <h2>💻 Technology Stack</h2>
        <p><strong>Frontend:</strong> React.js, Vite.js, Tailwind CSS</p>
        <p><strong>Backend:</strong> Node.js, Express.js</p>
        <p><strong>Database:</strong> MongoDB</p>
        <p><strong>Build Tool:</strong> Vite.js for fast development and hot module replacement.</p>

        <!-- Usage Instructions with Custom Styling -->
        <h2>📝 How to Use</h2>
        <ol>
            <li>Clone the repository and navigate to the backend directory:
                <pre><code>git clone https://github.com/Sandy1114D/Book-Store.git
cd Book-Store/backend</code></pre>
            </li>
            <li>Install backend dependencies:
                <pre><code>npm install</code></pre>
            </li>
            <li>Set up environment variables in a `.env` file:
                <pre><code>MONGO_URI=<Your MongoDB Connection String>
JWT_SECRET=<Your Secret Key></code></pre>
            </li>
            <li>Start the backend server:
                <pre><code>npm start</code></pre>
            </li>
            <li>Navigate to the frontend directory:
                <pre><code>cd ../frontend</code></pre>
            </li>
            <li>Install frontend dependencies:
                <pre><code>npm install</code></pre>
            </li>
            <li>Start the frontend development server:
                <pre><code>npm run dev</code></pre>
            </li>
            <li>Access the application at <a href="http://localhost:3000" class="button">http://localhost:3000</a></li>
        </ol>

        <!-- Screenshots Section -->
        <h2>📸 Screenshots</h2>
        <div class="img-gallery">
            <img src="https://via.placeholder.com/600x400.png?text=Homepage" alt="Homepage">
            <img src="https://via.placeholder.com/600x400.png?text=Books+Listing" alt="Books Listing">
            <img src="https://via.placeholder.com/600x400.png?text=Book+Details" alt="Book Details">
        </div>

        <!-- Contribution Guidelines with Custom Styling -->
        <h2>🤝 Contribution Guidelines</h2>
        <p>We welcome your contributions to enhance the Book Store Application. Please open issues or submit pull requests via <a href="https://github.com/Sandy1114D/Book-Store/issues" class="button">GitHub Issues</a>.</p>

        <!-- YouTube Video Section with Custom Styling -->
        <h2 class="centered">🎬 YouTube Video</h2>
        <div class="centered">
            <a href="https://www.youtube.com/watch?v=m87u3V9U-Z8">
                <img src="https://via.placeholder.com/600x400.png?text=Book+Store+Video" alt="Book Store Video">
            </a>
        </div>

        <!-- Acknowledgments Section with Custom Styling -->
        <h2 class="centered">🙏 Acknowledgments</h2>
        <p class="centered">Special thanks to all contributors and supporters of the Book Store Application.</p>
    </div>

    <!-- Add a Footer with Background Color -->
    <div class="footer">
        <h2>📖 Documentation</h2>
        <p><a href="https://github.com/Sandy1114D/Book-Store/blob/main/Documentation.pdf" class="button">Documentation</a></p>
        <p>For any questions or assistance, reach out to us at <a href="mailto:sanket3.r@gmail.com" class="button">sanket3.r@gmail.com</a></p>
    </div>
</body>
</html>
