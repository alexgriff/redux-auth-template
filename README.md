# Redux Auth Template

This repo works with this backend here:
**Make Sure you are on the `auth` branch of the backend**
https://github.com/alexgriff/painting-example-app-backend/tree/auth

This code is not meant to be copied and pasted wholesale. It should serve as an example to follow. You should build out your auth flow sequentially, using this repo like a code-along / guide.

_Note: In the `withAuth` HOC a lot of the complexity in the conditionals stems from the case of when an authenticated user refreshes the page on a route they are authorized to see. If that was ignored, everything would be significantly simpler._
