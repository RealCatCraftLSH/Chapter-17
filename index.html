<?php
    include 'config.php'

    $apiUrl = "https://api.nasa.gov/planetary/apod?api_key=" . $nasaAPIKey;
    $apiResponse = @file_get_contents($apiUrl);
    $nasaData = $apiRespone ? json_decode($apiResponse, true) : null;
?>

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>
            <?php
                echo isset($artwork['title'])
                    ? $artwork['title'] . " - Online Art Gallery"
                    : "Online Art Gallery - Nasa Feature";
            ?>
        </title>
        <meta name="description" content="<?php
            echo isset($artwork['title'])
                ? 'Learn About the Artwork ' . $artwork['title'] . ' by ' . $artwork['artist'] . '.' 
                : 'Browse artwork, artists, and collections in our online gallery.'
            ?>">
        <meta name="keywords" content="<?php
            echo isset($artwork['title'])
                ? $artwork['title'] . ', ' . $artwork['artist'] . [, painting, artwork, gallery'
                : ;art, painting, artists, gallery';
            ?>">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        <header>
            <h1>Online Art Gallery</h1>

            <nav>
                <ul>
                    <li><a href="/artists/">Browse All Artists</a></li>
                    <li><a href="/artworks/">View All Artworks</a></li>
                    <li><a href="/styles/">Explore Art Styles</a></li>
                </ul>
            </nav>
        </header>

        <main>
            <article>
                <section>
                    <h2>
                        <?php echo isset($artwork['title']) ? $artwork['title'] : "NASA Photo of the Day"; ?>
                    </h2>

                    <?php if($nasaData && isset($nasaData['url'])) : ?>
                        <img
                            src="<?php echo $nasaData['url']; ?>    "
                            alt="<?php echo $nasaData['title']; ?>"
                            title="<?php echo $nasaData['title']; ?>"
                            width="400"
                        >

                        <h3><?php echo $nasaData['title']; ?></h3>
                        <p><?php echo $nasaData['explanation']; ?></p>

                    <?php else : ?>
                        <p>Nasa image couldn't be loaded</p>
                    <?php endif; ?>
                </section>
                <section>
                    <h3>About the Artwork</h3>
                    <p>
                        <?php
                            echo isset($artwork['description'])
                                ? $artwork['description']
                                : "This artwork is part of our curated collection featuring notable pieces from various periods and styles"
                        ?>
                    </p>
                </section>

                <section>
                    <h3>About the Artist</h3>
                    <p>
                       <?php
                            echo isset($artwork['artistBio'])
                                ? $artwork['artistBio']
                                : "Learn more about the artists featured in our gallery"
                        ?> 
                    </p>
                </section>
            </article>
        </main>

        <footer>
            <p>&copy: <?php echo date("Y"); ?> Online Art Gallery</p>
        </footer>
    </body>
</html>
