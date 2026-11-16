# Google Sign In ClientID Example

This example demonstrates a basic client-side Google Sign-In flow using HTML and JavaScript. It highlights the critical role of the `client_id` and correct configuration of "Authorized JavaScript Origins" in the Google Cloud Console. These external configurations are often the source of "my code is fine, but it's not working" issues, which is the main topic of the accompanying article.

## Language

`html`

## How to Run

1. Replace `YOUR_GOOGLE_CLIENT_ID` in `index.html` with your actual Google Client ID from the Google Cloud Console.
2. In your Google Cloud Console, ensure `http://localhost:8000` is added to "Authorized JavaScript Origins" for your OAuth 2.0 Client ID.
3. Serve the `index.html` file using a simple HTTP server, e.g., `python -m http.server 8000` in the directory containing `index.html`.
4. Open your browser to `http://localhost:8000`.

## Original Article

This example accompanies the Turkish article: [Kullanıcılarım Google ile Giriş Yapamıyor: Hata Bende Değilse Neredeydi?](https://fatihsoysal.com/blog/kullanicilarim-google-ile-giris-yapamiyor-hata-bende-degilse-neredeydi/).

## License

MIT — see [LICENSE](LICENSE).
