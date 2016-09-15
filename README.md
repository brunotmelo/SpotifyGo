# SpotifyGo

## O que precisa pra rodar com o seu aplicativo
1. Setar o hash do debug keystore na pagina do aplicativo
 (Parte de "Creating a Development Fingerprint" no link https://developer.spotify.com/technologies/spotify-android-sdk/tutorial/)
2. Adicionar o callback "com.brunotmelo.spotifygologin://callback" na pagina do aplicativo
2. Botar a id do aplicativo na CLIENT_ID do MainActivity.java

## Known Bugs
1. Na versão atual(spotify-auth-beta21-noconnect-2.18c) o sdk da erro na autenticação caso você tenha o spotify instalado no celular.
2. Na versão atual o sdk não toca músicas e da um erro não identificado. (com.spotify.sdk.android.player.NativeSpotifyException: Failed SpPlayUri with error code 1 (The operation failed due to an unspecified issue))

