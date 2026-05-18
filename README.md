<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Flex Puzzle Project</title>

<style>

body{
    margin:0;
    font-family: Arial, sans-serif;
    background:#f0f0f0;
}

/* CSS GRID LAYOUT */
.container{
    display:grid;
    grid-template-columns: 1fr;
    grid-template-rows:auto auto auto;
    gap:20px;
    padding:20px;
}

/* Sections */
.section{
    background:white;
    padding:20px;
    border-radius:12px;
    box-shadow:0 2px 6px rgba(0,0,0,0.2);
}

/* Header */
.header{
    text-align:center;
    background:#4a90e2;
    color:white;
}

/* FLEXBOX PUZZLE */
.puzzle-container{
    display:flex;
    flex-wrap:wrap;
    width:600px;
    margin:auto;
    border:5px solid #333;
}

/* Puzzle pieces */
.puzzle-container img{
    width:200px;
    height:200px;
}

/* Hide incorrect piece */
.hidden-piece{
    display:none;
}

/* Footer */
.footer{
    text-align:center;
    background:#333;
    color:white;
}

</style>
</head>

<body>

<div class="container">

    <!-- Section 1 -->
    <div class="section header">
        <h1>Nasir Siraj</h1>
        <h2>Puzzle Project - Puzzle 1</h2>
    </div>

    <!-- Section 2 -->
    <div class="section">

        <h2 style="text-align:center;">Completed Flexbox Puzzle</h2>

        <div class="puzzle-container">

            <!-- Replace image names with actual file names from the zip folder -->

            <img src="images/piece1.jpg" alt="Puzzle Piece 1">
            <img src="images/piece2.jpg" alt="Puzzle Piece 2">
            <img src="images/piece3.jpg" alt="Puzzle Piece 3">

            <img src="images/piece4.jpg" alt="Puzzle Piece 4">
            <img src="images/piece5.jpg" alt="Puzzle Piece 5">
            <img src="images/piece6.jpg" alt="Puzzle Piece 6">

            <img src="images/piece7.jpg" alt="Puzzle Piece 7">
            <img src="images/piece8.jpg" alt="Puzzle Piece 8">
            <img src="images/piece9.jpg" alt="Puzzle Piece 9">

            <!-- Hidden incorrect puzzle piece -->
            <img src="images/wrongpiece.jpg" 
                 alt="Wrong Piece" 
                 class="hidden-piece">

        </div>
    </div>

    <!-- Section 3 -->
    <div class="section footer">
        <h3>Date Completed: May 18, 2026</h3>
    </div>

</div>

</body>
</html>
