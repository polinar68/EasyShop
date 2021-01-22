#EasyShop
. <script src="https://sdk.scdn.co/spotify-player.js"></script>
<script>
window.onSpotifyWebPlaybackSDKReady = () => {
  const userAccessToken = "[access 'pollyramos']";
  const webPlayback = new Spotify.Player({
    name: "Spotify Web Playback SDK",
    getOAuthToken: callback => { callback(userAccessToken)}
  });
  webPlayback.connect();
};
</script>
<!doctype html>
<html>
  <head>
    <!-- EasyShop,pollyramos -->
    <script src="https://kit.fontawesome.com/b5cd237f8b.js" crossorigin="anonymous"></script>
  </head>

  <body>
    <!-- Ready to use Font Awesome. Activate interlock. Dynotherms - connected. Infracells - up. Icons are go! -->
  </body>
</html>
