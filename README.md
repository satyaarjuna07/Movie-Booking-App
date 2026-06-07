# Movie-Booking-App
Movie Ticket Booking Application
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Andaman Movie Tickets</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#111;
    color:#fff;
}

header{
    background:#e50914;
    padding:15px 20px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:24px;
    font-weight:bold;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
}

.banner{
    height:400px;
    background:url('https://images.unsplash.com/photo-1489599849927-2ee91cede3ba')
    center/cover;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
}

.banner-content h1{
    font-size:50px;
    margin-bottom:10px;
}

.banner-content p{
    font-size:18px;
    margin-bottom:20px;
}

.btn{
    background:#e50914;
    color:white;
    padding:12px 25px;
    border:none;
    border-radius:5px;
    cursor:pointer;
}

.container{
    width:90%;
    margin:auto;
    padding:40px 0;
}

.section-title{
    margin-bottom:20px;
}

.movie-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.movie-card{
    background:#1e1e1e;
    border-radius:10px;
    overflow:hidden;
    transition:0.3s;
}

.movie-card:hover{
    transform:scale(1.05);
}

.movie-card img{
    width:100%;
    height:320px;
    object-fit:cover;
}

.movie-info{
    padding:15px;
}

.movie-info h3{
    margin-bottom:10px;
}

.book-btn{
    width:100%;
    padding:10px;
    background:#e50914;
    color:white;
    border:none;
    border-radius:5px;
    cursor:pointer;
}

footer{
    background:#000;
    text-align:center;
    padding:20px;
    margin-top:40px;
}
</style>
</head>

<body>

<header>
    <div class="logo">🎬 Andaman Movie Tickets</div>

    <nav>
        <a href="index.html">Home</a>
        <a href="my-bookings.html">My Bookings</a>
        <a href="login.html">Login</a>
        <a href="admin-login.html">Admin</a>
    </nav>
</header>

<section class="banner">
    <div class="banner-content">
        <h1>Book Movie Tickets Online</h1>
        <p>Easy, Fast & Secure Booking</p>
        <button class="btn" onclick="window.location.href='movie-details.html'">Book Now</button>
    </div>
</section>

<div class="container">

    <h2 class="section-title">Now Showing</h2>

    <div class="movie-grid">

        <div class="movie-card">
            <img src="https://via.placeholder.com/300x450" alt="">
            <div class="movie-info">
                <h3>Coolie</h3>
                <p>Action • Thriller</p>
                <br>
                <button class="book-btn" onclick="window.location.href='movie-details.html'">Book Tickets</button>
            </div>
        </div>

        <div class="movie-card">
            <img src="https://via.placeholder.com/300x450" alt="">
            <div class="movie-info">
                <h3>Kantara 2</h3>
                <p>Action • Drama</p>
                <br>
                <button class="book-btn" onclick="window.location.href='movie-details.html'">Book Tickets</button>
            </div>
        </div>

        <div class="movie-card">
            <img src="https://via.placeholder.com/300x450" alt="">
            <div class="movie-info">
                <h3>Avengers</h3>
                <p>Sci-Fi • Action</p>
                <br>
                <button class="book-btn" onclick="window.location.href='movie-details.html'">Book Tickets</button>
            </div>
        </div>

        <div class="movie-card">
            <img src="https://via.placeholder.com/300x450" alt="">
            <div class="movie-info">
                <h3>Mission Impossible</h3>
                <p>Action • Adventure</p>
                <br>
                <button class="book-btn" onclick="window.location.href='movie-details.html'">Book Tickets</button>
            </div>
        </div>

    </div>

</div>

<footer>
    <p>© 2026 Andaman Movie Tickets. All Rights Reserved.</p>
</footer>

</body>
</html>[Andaman movie tickets.txt](https://github.com/user-attachments/files/28682972/Andaman.movie.tickets.txt)
