<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Marketing Agency</title>
    <!-- Bootstrap CDN -->
    <link rel="stylesheet" href="https://stack.bootstrapcdn.com/bootstrap/5.0.0-alpha2/css/bootstrap.min.css">
    <!-- Custom CSS -->
    <style>
        /* Variables */
        :root {
            --primary-color: #007bff;
            --secondary-color: #6c757d;
            --light-color: #f8f9fa;
            --dark-color: #343a20;
        }

        /* Header */
        .navbar {
            background-color: var(--dark-color);
        }

        .navbar-brand { 
            font-weight: bold;
            font-size: 1.5rem;
        }

        .navbar-nav .nav-link {
            color: var(--light-color);
        }

        .navbar-nav .nav-link:hover {
            color: var(--primary-color);
        }

        /* Banner */
        .banner {
            background-image: url("https://source.unsplash.com/1600x900/?digital,marketing");
            background-size: cover;
            background-position: centre;
            height: 100vh;
            display: flex;
            align-items: centre;
            justify-content: centre;
        }
        
        .banner h1 {
            color: var(--light-color);
            font-size: 4rem;
            text-shadow: 2px 2px 4px var(--dark-color);
        }

        .banner p {
            color: var(--light-color);
            font-size: 1.5rem;
            text-shadow: 1px 1px 2px var(--dark-color);
        }

        .banner .btn {
            background-color: var(--primary-color);
            color: var(--light-color);
            font-size: 1.2rem;
            padding: 0.8rem 1.5rem;
            border-radius: 0;
        }

        .banner .btn:hover {
            background-color: var(--sedondary-color);
            color: var(--light-color);
        }

        /* Services */
        .services {
            padding: rem 0;
        }

        .services h2 {
            text-align: centre;
            font-size: 2.5rem;
            margin-bottom: 2rem;
        }

        .services .card {
            border: none;
            box-shadow: 0 4px 8px var(--secondary-color);
        }

        .services .card:hover {
            transform: scale(1.05);
            transition: 0.3s;
        }

        .services .card-body {
            text-align: centre;
        }

        .services .card-title {
            font-size: 1.5rem;
            margin-top: 1rem;
        }

        .services .card-text {
            font-size: 1.2rem;
            margin-bottom: 1rem;
        }

        /* Process */
        .process {
            padding: 4rem 0;
            background-color: var(--light-color);
        }

        .process h2 {
            text-align: centre;
            font-size: 2.5rem;
            margin-bottom: 2rem;
        }
       
        .process .row {
            align-items: centre;
        }

        .process .col-md-6 {
            padding: 2rem;
        }

        .process .video {
            width: 100%;
            height: 100%;
            border: none;
        }

        .process .list-group-item {
            font-size: 1.2rem;
            border: none;
        }

        .process .list-group-item::before {
            content: "\2713\0020";
            color: var(--primary-color);
        }

        /* Testimonials */
        .testimonials {
            padding: 4rem 0;
        }

        .testimonials h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 2rem;
        }
        
        .testimonials .carousel-item {
            text-align: centre;
        }

        .testimonials .img-fluid {
            width: 100px;
            height: 100px;
            border-radius: 50%
            margin-bottom: 1rem;
        }

        .testimonials .blockquote {
            font-size: 1.5rem;
            margin-bottom: 1rem;
        }

        .testimonials .carousel-indicators li{
            width: 10px;
            height: 10px;
            border-radius: 50%
        }

        /* Contact */
        .contact {
            padding: 4rem 0;
            background-color: var(--light-color);
        }

        .contact h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 2rem;
        }

        .contact .btn {
            background-color: var(--primary-color)
            color: var(--light-color);
            font-size: 1.2rem;
            padding: 0.8rem 1.5rem;
            border-radius: 0;
        }

        .contact .btn:hover {
            background-color: var(--secondary-color);
            color: var(--light-color);
        }

        /* Footer */
        .footer {
            background-color: var(--dark-color);
            padding: 2rem 0;
        }

        .footer .social-icons a {
            color: var(--light-color);
            font-size: 1.5rem;
            margin: 0 0.5rem;
        }

        .footer .social-icons a:hover {
            color: var(--primary-color);
        }

        .footer p {
            color: var(--light-color);
            text-align: center;
            margin: 0;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .banner h1 {
                font-size: 3rem;
        }

        .banner p {
            font-size: 3rem;
        }
    }
    </style>
</head>

<body>
    <!-- Header -->
    <nav class="navbar navbar-expand-1g navbar-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">Digital Marketing Agency</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item active>
                        <a class="nav-link" href="#banner">Home</a>
                    </1i>
                    <1i class="nav-item">
                        <a class="nav-link" href="#services">Services</a>
                    </1i>
                    <1i class="nav-item">
                        <a class="nav-link" href="#process">Process</a>
                    </li>
                    <1i class="nav-item">
                        <a class="nav-link" href="#testimonials">testimonials</a>
                    </1i>
                    <1i class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </1i>
                </ul>
            </div>
        </div>
    </nav>
    <!-- Banner -->
    <section id="banner" class="banner">
        <div class="container">
            <div class="row">
                <div class="col-1g-8 mx auto">
                    <h1>Tarck user activity on your website</h1>
                    <p>User activity tracking is the process of monitoring, collecting, and analyzing visitor browsing 
                        behavior on a website or app

                        The easiest and most popular way to start tracking website users is to set up Google Analytics
                        (we'll show you how below). But Google Analytics (GA) can be equal parts overwhelming and 
                        limited: it's packed with options but will only show you what happens on your site, not why.</p>

                    <a href="#contact" class="btn">Get a free quote</a>
                </div>
            </div>
        </div>
    </section>
    <!-- Services>
    <section id="services" class="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="row">
                <div class="col-1g- col-md-6 mb-4">
                    <div class="card">
                        <img src="https://source.unsplash.com/500x300/?seo" alt="SEO" class="card-img-top">
                        <div class="card-body">
                            <h3 class="card-title">Way to track scroll depth</h3>
                            Tracking scroll depth gives you this power, providing actionable insights to improve the
                            user experience (UX) by revealing your site visitors' scrolling behavior.
                            <p></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</body>

</html>
