<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        
        header {
            background: #2c3e50;
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        
        main {
            max-width: 800px;
            margin: 3rem auto;
            padding: 0 2rem;
        }
        
        .contact-section {
            background: #f4f4f4;
            padding: 2rem;
            border-radius: 8px;
        }
        
        h2 {
            color: #2c3e50;
            margin-bottom: 1.5rem;
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: bold;
        }
        
        input, textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 1rem;
            font-family: Arial, sans-serif;
        }
        
        textarea {
            resize: vertical;
            min-height: 150px;
        }
        
        button {
            background: #2c3e50;
            color: white;
            padding: 1rem 2rem;
            border: none;
            border-radius: 4px;
            font-size: 1rem;
            cursor: pointer;
            transition: background 0.3s;
        }
        
        button:hover {
            background: #34495e;
        }
        
        button:disabled {
            background: #95a5a6;
            cursor: not-allowed;
        }
        
        .success-message {
            display: none;
            background: #2ecc71;
            color: white;
            padding: 1rem;
            border-radius: 4px;
            margin-bottom: 1rem;
        }
        
        .error-message {
            display: none;
            background: #e74c3c;
            color: white;
            padding: 1rem;
            border-radius: 4px;
            margin-bottom: 1rem;
        }
        
        footer {
            text-align: center;
            padding: 2rem;
            background: #2c3e50;
            color: white;
            margin-top: 3rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our Website</h1>
        <p>We'd love to hear from you</p>
    </header>
    
    <main>
        <section class="contact-section">
            <h2>Contact Us</h2>
            
            <div class="success-message" id="successMessage">
                Thank you for your message! We'll get back to you soon.
            </div>
            
            <div class="error-message" id="errorMessage">
                Sorry, there was an error sending your message. Please try again.
            </div>
            
            <form id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required>
                </div>
                
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                
                <div class="form-group">
                    <label for="subject">Subject:</label>
                    <input type="text" id="subject" name="subject" required>
                </div>
                
                <div class="form-group">
                    <label for="message">Message:</label>
                    <textarea id="message" name="message" required></textarea>
                </div>
                
                <button type="submit" id="submitBtn">Send Message</button>
            </form>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2026 Your Company. All rights reserved.</p>
    </footer>
    
    <script>
        const form = document.getElementById('contactForm');
        const submitBtn = document.getElementById('submitBtn');
        const successMsg = document.getElementById('successMessage');
        const errorMsg = document.getElementById('errorMessage');
        
        form.addEventListener('submit', async function(e) {
            e.preventDefault();
            
            // Disable button and show loading state
            submitBtn.disabled = true;
            submitBtn.textContent = 'Sending...';
            successMsg.style.display = 'none';
            errorMsg.style.display = 'none';
            
            try {
                const formData = new FormData(form);
                const response = await fetch(form.action, {
                    method: 'POST',
                    body: formData,
                    headers: {
                        'Accept': 'application/json'
                    }
                });
                
                if (response.ok) {
                    successMsg.style.display = 'block';
                    form.reset();
                } else {
                    errorMsg.style.display = 'block';
                }
            } catch (error) {
                errorMsg.style.display = 'block';
            } finally {
                submitBtn.disabled = false;
                submitBtn.textContent = 'Send Message';
            }
        });
    </script>
</body>
</html>
