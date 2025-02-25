# Prototype-HTML5-Assignment<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8" /> <!-- Specifies the character encoding -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" /> <!-- Ensures responsiveness -->
    <meta name="description" content="HTML Prototype Document" /> <!-- Provides a description of the page -->
    <meta name="author" content="Your Name" /> <!-- Specifies the author of the document -->
    <title>HTML Prototype</title> <!-- Defines the title of the document -->
</head>
<body>
    <main> <!-- Surrounds all elements within the body -->
        <header> <!-- Surrounds <h1> text -->
            <h1>Welcome to My HTML Prototype</h1>
        </header>
        
        <nav> <!-- Navigation Section -->
            <ul>
                <li><a href="index.html" title="Home">Home</a></li>
                <li><a href="https://en.wikipedia.org/wiki/University_of_Arkansas_at_Little_Rock" title="About">About</a></li>
                <li><a href="https://ualr.edu" target="_blank" title="UALR">UALR</a></li>
                <li><a href="mailto:your@email.com" title="Contact">Contact</a></li>
            </ul>
        </nav>
        
        <section id="content"> <!-- Main Content Section -->
            <h2>Subheading Level 2</h2>
            <h3>Subheading Level 3</h3>
            <h4>Subheading Level 4</h4>
            <h5>Subheading Level 5</h5>
            
            <p>This is a paragraph with <strong>strong emphasis</strong> and <em>italicized emphasis</em>.</p>
            
            <h3>Lists</h3>
            <ol>
                <li>First ordered item</li>
                <li>Second ordered item</li>
                <li>Third ordered item</li>
            </ol>
            <ul>
                <li>First unordered item</li>
                <li>Second unordered item</li>
                <li>Third unordered item</li>
            </ul>
            <dl>
                <dt>Term</dt>
                <dd>Definition of the term.</dd>
            </dl>
            
            <h3>Quotes</h3>
            <p>Inline quote example: <q>Success is not final, failure is not fatal.</q></p>
            <blockquote>
                <p>This is a blockquote example. It can be longer and span multiple lines.</p>
            </blockquote>
            
            <h3>Sample Table</h3>
            <table>
                <caption>Example Table</caption>
                <tr>
                    <th scope="col">Column 1</th>
                    <th scope="col">Column 2</th>
                    <th scope="col">Column 3</th>
                    <th scope="col">Column 4</th>
                    <th scope="col">Column 5</th>
                </tr>
                <tr>
                    <td>Row 1, Col 1</td>
                    <td>Row 1, Col 2</td>
                    <td>Row 1, Col 3</td>
                    <td>Row 1, Col 4</td>
                    <td>Row 1, Col 5</td>
                </tr>
                <tr>
                    <td>Row 2, Col 1</td>
                    <td>Row 2, Col 2</td>
                    <td>Row 2, Col 3</td>
                    <td>Row 2, Col 4</td>
                    <td>Row 2, Col 5</td>
                </tr>
                <tr>
                    <td>Row 3, Col 1</td>
                    <td>Row 3, Col 2</td>
                    <td>Row 3, Col 3</td>
                    <td>Row 3, Col 4</td>
                    <td>Row 3, Col 5</td>
                </tr>
                <tr>
                    <td>Row 4, Col 1</td>
                    <td>Row 4, Col 2</td>
                    <td>Row 4, Col 3</td>
                    <td>Row 4, Col 4</td>
                    <td>Row 4, Col 5</td>
                </tr>
                <tr>
                    <td>Row 5, Col 1</td>
                    <td>Row 5, Col 2</td>
                    <td>Row 5, Col 3</td>
                    <td>Row 5, Col 4</td>
                    <td>Row 5, Col 5</td>
                </tr>
            </table>
            
            <h3>Image</h3>
            <img src="https://via.placeholder.com/150" alt="Placeholder Image" width="150" height="150" />
        </section> <!-- Closing content section -->
        
        <footer> <!-- Footer Section -->
            <h6>&copy; 2025 Your Name. <a href="mailto:your@email.com">Email Me</a>. <a href="#top">Back to Top</a></h6>
        </footer>
    </main> <!-- Closing main section -->
</body>
</html>
