# Pic-to-pdf <!DOCTYPE html>
<html lang="en">
<head>
    <!-- SEO Meta Tags -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Convert your images to high-quality PDF files instantly. Free online tool with no registration required.">
    <meta name="keywords" content="image to pdf, jpg to pdf, png to pdf, convert image to pdf, free pdf converter">
    <meta name="author" content="Jasminder Singh">
    <meta name="robots" content="index, follow">
    
    <!-- Open Graph / Social Media Meta Tags -->
    <meta property="og:title" content="Pic to PDF - Convert Images to PDF Online">
    <meta property="og:description" content="Free online tool to convert your images to high-quality PDF files instantly.">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://jasmindersingh28.github.io/Pic-to-pdf">
    <meta property="og:image" content="https://jasmindersingh28.github.io/Pic-to-pdf/assets/og-image.jpg">
    
    <!-- Favicon -->
    <link rel="icon" href="assets/favicon.ico" type="image/x-icon">
    
    <!-- Canonical URL -->
    <link rel="canonical" href="https://jasmindersingh28.github.io/Pic-to-pdf">
    
    <title>Pic to PDF - Convert Images to High-Quality PDF Online</title>
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    
    <!-- Google AdSense -->
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client="ca-app-pub-7482977341817103/4693896190"></script>
    
    <style>
        :root {
            --primary-color: #4a6bff;
            --secondary-color: #6c5ce7;
            --accent-color: #00cec9;
            --light-color: #f8f9fa;
            --dark-color: #343a40;
            --success-color: #2ecc71;
            --warning-color: #f39c12;
            --danger-color: #e74c3c;
            --gray-color: #95a5a6;
            --border-radius: 8px;
            --box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            --transition: all 0.3s ease;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f5f7ff;
        }

        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background-color: white;
            box-shadow: var(--box-shadow);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .logo img {
            height: 40px;
        }

        .logo h1 {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary-color);
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 25px;
        }

        nav a {
            text-decoration: none;
            color: var(--dark-color);
            font-weight: 500;
            transition: var(--transition);
        }

        nav a:hover {
            color: var(--primary-color);
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: white;
            color: var(--primary-color);
            border: 2px solid var(--primary-color);
            border-radius: var(--border-radius);
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
            text-align: center;
        }

        .btn:hover {
            background-color: var(--primary-color);
            color: white;
        }

        .btn.primary {
            background-color: var(--primary-color);
            color: white;
        }

        .btn.primary:hover {
            background-color: #3a56d4;
            border-color: #3a56d4;
        }

        .hero {
            text-align: center;
            padding: 50px 0 30px;
        }

        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 15px;
            color: var(--dark-color);
        }

        .hero p {
            font-size: 1.1rem;
            color: var(--gray-color);
            margin-bottom: 30px;
        }

        .upload-area {
            border: 2px dashed var(--primary-color);
            border-radius: var(--border-radius);
            padding: 40px 20px;
            margin: 0 auto 30px;
            max-width: 600px;
            background-color: rgba(74, 107, 255, 0.05);
            transition: var(--transition);
            position: relative;
        }

        .upload-area:hover {
            background-color: rgba(74, 107, 255, 0.1);
        }

        .upload-area i {
            font-size: 3rem;
            color: var(--primary-color);
            margin-bottom: 15px;
        }

        .upload-area p {
            margin-bottom: 15px;
            color: var(--dark-color);
        }

        .upload-area .formats {
            font-size: 0.9rem;
            color: var(--gray-color);
            margin-top: 15px;
        }

        #fileInput {
            display: none;
        }

        .ad-container {
            margin: 30px auto;
            text-align: center;
            overflow: hidden;
            border-radius: var(--border-radius);
        }

        .options-section {
            background-color: white;
            padding: 30px;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            margin-bottom: 30px;
        }

        .options {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }

        .option {
            display: flex;
            flex-direction: column;
        }

        .option label {
            margin-bottom: 8px;
            font-weight: 500;
            color: var(--dark-color);
        }

        .option input, .option select {
            padding: 10px 15px;
            border: 1px solid #ddd;
            border-radius: var(--border-radius);
            font-family: 'Poppins', sans-serif;
            transition: var(--transition);
        }

        .option input:focus, .option select:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 0 2px rgba(74, 107, 255, 0.2);
        }

        #convertBtn {
            display: block;
            width: 100%;
            max-width: 300px;
            margin: 0 auto;
            padding: 12px;
            font-size: 1.1rem;
        }

        #convertBtn:disabled {
            background-color: #ccc;
            border-color: #ccc;
            cursor: not-allowed;
        }

        .preview-section {
            background-color: white;
            padding: 30px;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            margin-bottom: 30px;
        }

        .preview-section h3 {
            margin-bottom: 20px;
            color: var(--dark-color);
        }

        .image-preview {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            gap: 15px;
            margin-bottom: 20px;
        }

        .preview-image {
            position: relative;
            border-radius: var(--border-radius);
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
        }

        .preview-image img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            display: block;
        }

        .preview-image .remove-btn {
            position: absolute;
            top: 5px;
            right: 5px;
            background-color: var(--danger-color);
            color: white;
            border: none;
            width: 25px;
            height: 25px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            opacity: 0;
            transition: var(--transition);
        }

        .preview-image:hover .remove-btn {
            opacity: 1;
        }

        .file-info {
            font-size: 0.9rem;
            color: var(--gray-color);
        }

        .features-section {
            text-align: center;
            padding: 60px 0 30px;
        }

        .features-section h2 {
            margin-bottom: 40px;
            color: var(--dark-color);
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .feature {
            background-color: white;
            padding: 30px 20px;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            transition: var(--transition);
        }

        .feature:hover {
            transform: translateY(-5px);
        }

        .feature i {
            font-size: 2.5rem;
            color: var(--primary-color);
            margin-bottom: 20px;
        }

        .feature h3 {
            margin-bottom: 15px;
            color: var(--dark-color);
        }

        .how-it-works {
            text-align: center;
            padding: 60px 0;
            background-color: #f8f9fa;
        }

        .how-it-works h2 {
            margin-bottom: 40px;
            color: var(--dark-color);
        }

        .steps {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .step {
            position: relative;
            padding: 30px 20px;
        }

        .step-number {
            width: 50px;
            height: 50px;
            background-color: var(--primary-color);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            font-weight: 700;
            margin: 0 auto 20px;
        }

        .step h3 {
            margin-bottom: 15px;
            color: var(--dark-color);
        }

        .faq-section {
            padding: 60px 0;
        }

        .faq-section h2 {
            text-align: center;
            margin-bottom: 40px;
            color: var(--dark-color);
        }

        .faq-container {
            max-width: 800px;
            margin: 0 auto;
        }

        .faq-item {
            margin-bottom: 15px;
            border-radius: var(--border-radius);
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
        }

        .faq-question {
            width: 100%;
            padding: 20px;
            background-color: white;
            border: none;
            text-align: left;
            font-weight: 600;
            font-size: 1.1rem;
            color: var(--dark-color);
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
            transition: var(--transition);
        }

        .faq-question:hover {
            background-color: #f8f9fa;
        }

        .faq-question i {
            transition: var(--transition);
        }

        .faq-question.active i {
            transform: rotate(180deg);
        }

        .faq-answer {
            padding: 0 20px;
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease;
            background-color: white;
        }

        .faq-answer p {
            padding: 0 0 20px;
        }

        footer {
            background-color: var(--dark-color);
            color: white;
            padding: 60px 0 0;
        }

        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }

        .footer-section h4 {
            font-size: 1.2rem;
            margin-bottom: 20px;
            color: white;
        }

        .footer-section ul {
            list-style: none;
        }

        .footer-section ul li {
            margin-bottom: 10px;
        }

        .footer-section ul li a {
            color: #ddd;
            text-decoration: none;
            transition: var(--transition);
        }

        .footer-section ul li a:hover {
            color: white;
        }

        .social-links {
            display: flex;
            gap: 15px;
        }

        .social-links a {
            color: white;
            font-size: 1.2rem;
            transition: var(--transition);
        }

        .social-links a:hover {
            color: var(--primary-color);
        }

        .footer-bottom {
            text-align: center;
            padding: 20px 0;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            font-size: 0.9rem;
            color: #aaa;
        }

        .footer-bottom a {
            color: var(--primary-color);
            text-decoration: none;
        }

        /* Drag and Drop Styles */
        #dropArea.highlight {
            background-color: rgba(74, 107, 255, 0.2);
            border-color: var(--accent-color);
        }

        /* Responsive Styles */
        @media (max-width: 768px) {
            header .container {
                flex-direction: column;
                gap: 15px;
            }
            
            nav ul {
                gap: 15px;
            }
            
            .hero h2 {
                font-size: 2rem;
            }
            
            .options {
                grid-template-columns: 1fr;
            }
            
            #convertBtn {
                max-width: 100%;
            }
        }

        @media (max-width: 480px) {
            .hero h2 {
                font-size: 1.8rem;
            }
            
            .upload-area {
                padding: 30px 15px;
            }
            
            .faq-question {
                font-size: 1rem;
                padding: 15px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <img src="assets/logo.png" alt="Pic to PDF Logo">
                <h1>Pic to PDF</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#features">Features</a></li>
                    <li><a href="#how-it-works">How It Works</a></li>
                    <li><a href="#faq">FAQ</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container">
        <section class="hero">
            <div class="hero-content">
                <h2>Convert Images to PDF in Seconds</h2>
                <p>High-quality PDF conversion with no watermarks. Free and easy to use!</p>
                <div class="upload-area" id="dropArea">
                    <i class="fas fa-cloud-upload-alt"></i>
                    <p>Drag & Drop your images here or</p>
                    <input type="file" id="fileInput" accept="image/*" multiple>
                    <button class="btn">Browse Files</button>
                    <p class="formats">Supports: JPG, PNG, GIF, BMP, WEBP</p>
                </div>
            </div>
            
            <!-- AdSense Banner Ad -->
            <div class="ad-container">
                <ins class="adsbygoogle"
                     style="display:block"
                     data-ad-client="ca-app-pub-7482977341817103/4693896190"
                     data-ad-slot="4693896190"
                     data-ad-format="auto"
                     data-full-width-responsive="true"></ins>
                <script>
                     (adsbygoogle = window.adsbygoogle || []).push({});
                </script>
            </div>
        </section>

        <section class="options-section">
            <div class="options">
                <div class="option">
                    <label for="pdfName">PDF Name:</label>
                    <input type="text" id="pdfName" placeholder="output.pdf">
                </div>
                <div class="option">
                    <label for="pageSize">Page Size:</label>
                    <select id="pageSize">
                        <option value="a4">A4</option>
                        <option value="letter">Letter</option>
                        <option value="legal">Legal</option>
                        <option value="fit">Fit to Image</option>
                    </select>
                </div>
                <div class="option">
                    <label for="pageOrientation">Orientation:</label>
                    <select id="pageOrientation">
                        <option value="portrait">Portrait</option>
                        <option value="landscape">Landscape</option>
                    </select>
                </div>
                <div class="option">
                    <label for="margin">Margin (mm):</label>
                    <input type="number" id="margin" min="0" max="50" value="10">
                </div>
            </div>
            <button id="convertBtn" class="btn primary" disabled>Convert to PDF</button>
        </section>

        <section class="preview-section">
            <h3>Selected Images</h3>
            <div id="imagePreview" class="image-preview"></div>
            <div id="fileInfo" class="file-info"></div>
        </section>

        <section id="features" class="features-section">
            <h2>Why Choose Our Image to PDF Converter?</h2>
            <div class="features-grid">
                <div class="feature">
                    <i class="fas fa-bolt"></i>
                    <h3>Fast Conversion</h3>
                    <p>Convert multiple images to PDF in seconds with our optimized processing.</p>
                </div>
                <div class="feature">
                    <i class="fas fa-lock"></i>
                    <h3>Secure & Private</h3>
                    <p>Your files never leave your browser. No server uploads, complete privacy.</p>
                </div>
                <div class="feature">
                    <i class="fas fa-star"></i>
                    <h3>High Quality</h3>
                    <p>Preserve original image quality in the output PDF with no compression.</p>
                </div>
                <div class="feature">
                    <i class="fas fa-cog"></i>
                    <h3>Customizable</h3>
                    <p>Adjust page size, orientation, and margins to fit your needs.</p>
                </div>
            </div>
        </section>

        <section id="how-it-works" class="how-it-works">
            <h2>How It Works</h2>
            <div class="steps">
                <div class="step">
                    <div class="step-number">1</div>
                    <h3>Upload Images</h3>
                    <p>Drag & drop or select multiple images from your device.</p>
                </div>
                <div class="step">
                    <div class="step-number">2</div>
                    <h3>Adjust Settings</h3>
                    <p>Choose PDF name, page size, orientation, and margins.</p>
                </div>
                <div class="step">
                    <div class="step-number">3</div>
                    <h3>Convert & Download</h3>
                    <p>Click convert and get your PDF file instantly.</p>
                </div>
            </div>
        </section>

        <section id="faq" class="faq-section">
            <h2>Frequently Asked Questions</h2>
            <div class="faq-container">
                <div class="faq-item">
                    <button class="faq-question">Is this service really free?<i class="fas fa-chevron-down"></i></button>
                    <div class="faq-answer">
                        <p>Yes, our image to PDF converter is completely free to use with no hidden charges. You can convert as many images as you want without any limitations.</p>
                    </div>
                </div>
                <div class="faq-item">
                    <button class="faq-question">Will my images be compressed?<i class="fas fa-chevron-down"></i></button>
                    <div class="faq-answer">
                        <p>No, we preserve the original quality of your images in the PDF output. The conversion process doesn't reduce image quality.</p>
                    </div>
                </div>
                <div class="faq-item">
                    <button class="faq-question">Where are my files processed?<i class="fas fa-chevron-down"></i></button>
                    <div class="faq-answer">
                        <p>All processing happens directly in your browser. Your images never leave your device, ensuring complete privacy and security.</p>
                    </div>
                </div>
                <div class="faq-item">
                    <button class="faq-question">What image formats are supported?<i class="fas fa-chevron-down"></i></button>
                    <div class="faq-answer">
                        <p>We support JPG, PNG, GIF, BMP, and WEBP formats. You can mix different formats in a single conversion.</p>
                    </div>
                </div>
                <div class="faq-item">
                    <button class="faq-question">Can I rearrange images before converting?<i class="fas fa-chevron-down"></i></button>
                    <div class="faq-answer">
                        <p>Yes, you can drag and drop images in the preview area to reorder them before conversion to PDF.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- AdSense In-Article Ad -->
        <div class="ad-container">
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-client="ca-app-pub-7482977341817103/4693896190"
                 data-ad-slot="4693896190"
                 data-ad-format="auto"
                 data-full-width-responsive="true"></ins>
            <script>
                 (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
    </main>

    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h4>Pic to PDF</h4>
                    <p>A free online tool to convert your images to high-quality PDF files instantly.</p>
                </div>
                <div class="footer-section">
                    <h4>Quick Links</h4>
                    <ul>
                        <li><a href="#features">Features</a></li>
                        <li><a href="#how-it-works">How It Works</a></li>
                        <li><a href="#faq">FAQ</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h4>Connect</h4>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-github"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; <span id="year"></span> Pic to PDF. All rights reserved. Created by <a href="https://github.com/jasmindersingh28">Jasminder Singh</a></p>
            </div>
        </div>
    </footer>

    <!-- Scripts -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>
    
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Set current year in footer
            document.getElementById('year').textContent = new Date().getFullYear();
            
            // Initialize variables
            const fileInput = document.getElementById('fileInput');
            const dropArea = document.getElementById('dropArea');
            const convertBtn = document.getElementById('convertBtn');
            const imagePreview = document.getElementById('imagePreview');
            const fileInfo = document.getElementById('fileInfo');
            const pdfNameInput = document.getElementById('pdfName');
            const pageSizeSelect = document.getElementById('pageSize');
            const pageOrientationSelect = document.getElementById('pageOrientation');
            const marginInput = document.getElementById('margin');
            
            let files = [];
            
            // Initialize PDF.js
            const { jsPDF } = window.jspdf;
            
            // Setup drag and drop
            ['dragenter', 'dragover', 'dragleave', 'drop'].forEach(eventName => {
                dropArea.addEventListener(eventName, preventDefaults, false);
            });
            
            function preventDefaults(e) {
                e.preventDefault();
                e.stopPropagation();
            }
            
            ['dragenter', 'dragover'].forEach(eventName => {
                dropArea.addEventListener(eventName, highlight, false);
            });
            
            ['dragleave', 'drop'].forEach(eventName => {
                dropArea.addEventListener(eventName, unhighlight, false);
            });
            
            function highlight() {
                dropArea.classList.add('highlight');
            }
            
            function unhighlight() {
                dropArea.classList.remove('highlight');
            }
            
            // Handle dropped files
            dropArea.addEventListener('drop', handleDrop, false);
            
            function handleDrop(e) {
                const dt = e.dataTransfer;
                const newFiles = dt.files;
                handleFiles(newFiles);
            }
            
            // Handle file input
            fileInput.addEventListener('change', function() {
                handleFiles(this.files);
            });
            
            // Browse button click
            dropArea.querySelector('button').addEventListener('click', function() {
                fileInput.click();
            });
            
            // Handle selected files
            function handleFiles(newFiles) {
                files = Array.from(newFiles);
                
                // Filter only image files
                files = files.filter(file => file.type.match('image.*'));
                
                if (files.length === 0) {
                    alert('Please select only image files (JPG, PNG, GIF, BMP, WEBP).');
                    return;
                }
                
                updateFileInfo();
                displayImagePreviews();
                convertBtn.disabled = false;
                
                // Set default PDF name
                if (files.length === 1) {
                    pdfNameInput.value = files[0].name.replace(/\.[^/.]+$/, '') + '.pdf';
                } else {
                    pdfNameInput.value = 'images.pdf';
                }
            }
            
            // Update file information display
            function updateFileInfo() {
                const totalSize = files.reduce((sum, file) => sum + file.size, 0);
                const sizeInMB = (totalSize / (1024 * 1024)).toFixed(2);
                
                fileInfo.innerHTML = `
                    <p>${files.length} ${files.length === 1 ? 'image' : 'images'} selected (${sizeInMB} MB)</p>
                `;
            }
            
            // Display image previews
            function displayImagePreviews() {
                imagePreview.innerHTML = '';
                
                files.forEach((file, index) => {
                    const reader = new FileReader();
                    
                    reader.onload = function(e) {
                        const previewImage = document.createElement('div');
                        previewImage.className = 'preview-image';
                        previewImage.draggable = true;
                        previewImage.dataset.index = index;
                        
                        previewImage.innerHTML = `
                            <img src="${e.target.result}" alt="${file.name}">
                            <button class="remove-btn" data-index="${index}">
                                <i class="fas fa-times"></i>
                            </button>
                        `;
                        
                        imagePreview.appendChild(previewImage);
                        
                        // Add remove button event
                        previewImage.querySelector('.remove-btn').addEventListener('click', function() {
                            removeImage(index);
                        });
                        
                        // Add drag events for reordering
                        previewImage.addEventListener('dragstart', handleDragStart);
                        previewImage.addEventListener('dragover', handleDragOver);
                        previewImage.addEventListener('drop', handleDropReorder);
                        previewImage.addEventListener('dragend', handleDragEnd);
                    };
                    
                    reader.readAsDataURL(file);
                });
            }
            
            // Remove image from selection
            function removeImage(index) {
                files.splice(index, 1);
                
                if (files.length === 0) {
                    convertBtn.disabled = true;
                    fileInfo.innerHTML = '';
                } else {
                    updateFileInfo();
                }
                
                displayImagePreviews();
            }
            
            // Drag and drop for reordering images
            let draggedItem = null;
            
            function handleDragStart(e) {
                draggedItem = this;
                e.dataTransfer.effectAllowed = 'move';
                e.dataTransfer.setData('text/html', this.innerHTML);
                this.style.opacity = '0.4';
            }
            
            function handleDragOver(e) {
                e.preventDefault();
                e.dataTransfer.dropEffect = 'move';
                return false;
            }
            
            function handleDropReorder(e) {
                e.stopPropagation();
                e.preventDefault();
                
                if (draggedItem !== this) {
                    // Get indices of dragged item and drop target
                    const fromIndex = parseInt(draggedItem.dataset.index);
                    const toIndex = parseInt(this.dataset.index);
                    
                    // Reorder files array
                    const [movedFile] = files.splice(fromIndex, 1);
                    files.splice(toIndex, 0, movedFile);
                    
                    // Update previews
                    displayImagePreviews();
                }
                
                return false;
            }
            
            function handleDragEnd() {
                this.style.opacity = '1';
            }
            
            // Convert to PDF
            convertBtn.addEventListener('click', convertToPDF);
            
            async function convertToPDF() {
                if (files.length === 0) return;
                
                convertBtn.disabled = true;
                convertBtn.innerHTML = '<i class="fas fa-spinner fa-spin"></i> Converting...';
                
                try {
                    // Create PDF
                    const pdf = new jsPDF({
                        orientation: pageOrientationSelect.value,
                        unit: 'mm'
                    });
                    
                    // Get page size in mm
                    let pageWidth, pageHeight;
                    
                    switch (pageSizeSelect.value) {
                        case 'a4':
                            pageWidth = 210;
                            pageHeight = 297;
                            break;
                        case 'letter':
                            pageWidth = 215.9;
                            pageHeight = 279.4;
                            break;
                        case 'legal':
                            pageWidth = 215.9;
                            pageHeight = 355.6;
                            break;
                        case 'fit':
                            // Will be handled per image
                            break;
                        default:
                            pageWidth = 210;
                            pageHeight = 297;
                    }
                    
                    const margin = parseInt(marginInput.value) || 0;
                    
                    // Process each image
                    for (let i = 0; i < files.length; i++) {
                        const file = files[i];
                        const img = await loadImage(file);
                        
                        if (pageSizeSelect.value === 'fit') {
                            // Fit to image dimensions
                            const imgWidth = img.width * 0.264583; // px to mm
                            const imgHeight = img.height * 0.264583; // px to mm
                            
                            pdf.addPage([imgWidth + margin * 2, imgHeight + margin * 2], imgWidth > imgHeight ? 'landscape' : 'portrait');
                            pdf.addImage(img, 'JPEG', margin, margin, imgWidth, imgHeight);
                        } else {
                            // Calculate dimensions to fit page with margins
                            const availableWidth = pageWidth - margin * 2;
                            const availableHeight = pageHeight - margin * 2;
                            
                            let imgWidth, imgHeight;
                            const imgAspectRatio = img.width / img.height;
                            const pageAspectRatio = availableWidth / availableHeight;
                            
                            if (imgAspectRatio > pageAspectRatio) {
                                // Image is wider relative to its height than page is
                                imgWidth = availableWidth;
                                imgHeight = availableWidth / imgAspectRatio;
                            } else {
                                // Image is taller relative to its width than page is
                                imgHeight = availableHeight;
                                imgWidth = availableHeight * imgAspectRatio;
                            }
                            
                            // Center the image on the page
                            const x = margin + (availableWidth - imgWidth) / 2;
                            const y = margin + (availableHeight - imgHeight) / 2;
                            
                            if (i > 0) pdf.addPage();
                            pdf.addImage(img, 'JPEG', x, y, imgWidth, imgHeight);
                        }
                    }
                    
                    // Save PDF
                    pdf.save(pdfNameInput.value || 'output.pdf');
                    
                } catch (error) {
                    console.error('Error converting to PDF:', error);
                    alert('An error occurred while converting to PDF. Please try again.');
                } finally {
                    convertBtn.disabled = false;
                    convertBtn.textContent = 'Convert to PDF';
                }
            }
            
            // Load image and return promise
            function loadImage(file) {
                return new Promise((resolve, reject) => {
                    const img = new Image();
                    const reader = new FileReader();
                    
                    reader.onload = function(e) {
                        img.src = e.target.result;
                    };
                    
                    img.onload = function() {
                        resolve(img);
                    };
                    
                    img.onerror = function() {
                        reject(new Error('Failed to load image'));
                    };
                    
                    reader.readAsDataURL(file);
                });
            }
            
            // FAQ accordion functionality
            const faqQuestions = document.querySelectorAll('.faq-question');
            
            faqQuestions.forEach(question => {
                question.addEventListener('click', function() {
                    this.classList.toggle('active');
                    const answer = this.nextElementSibling;
                    
                    if (answer.style.maxHeight) {
                        answer.style.maxHeight = null;
                    } else {
                        answer.style.maxHeight = answer.scrollHeight + 'px';
                    }
                });
            });
        });
    </script>
    
    <!-- Structured Data for SEO -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "WebApplication",
        "name": "Pic to PDF Converter",
        "url": "https://jasmindersingh28.github.io/Pic-to-pdf",
        "description": "Free online tool to convert images to high-quality PDF files instantly.",
        "applicationCategory": "UtilityApplication",
        "operatingSystem": "Web Browser",
        "offers": {
            "@type": "Offer",
            "price": "0",
            "priceCurrency": "USD"
        },
        "creator": {
            "@type": "Person",
            "name": "Jasminder Singh"
        }
    }
    </script>
</body>
</html>
