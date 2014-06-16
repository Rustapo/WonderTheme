# Readme

To install this theme, just unzip `jumbotron.zip` into your "themes" folder in WonderCMS. (It should automatically expand into a folder called 'jumbotron').

You can also just download the `public_html` folder, which includes a default WonderCMS (v0.6 BETA) installation.

If you are installing `jumbotron.zip` into your own WonderCMS installation (not using the `public_html` folder included here), you will need to make one modification to your index.php file. On line 21, add:

    include ('themes/jumbotron/default-content.php');

If you have any trouble, please open an issue on the github repo at https://github.com/cristoslc/WonderCMS-Jumbotron/issues