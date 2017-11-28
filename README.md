# Script error demo

How to use (instructions should work for OS X or Linux):

1. In your `/etc/hosts`, add an alias `otherdomain` for `127.0.0.1`. For example:
    
    ```
    127.0.0.1   localhost otherdomain
    ```

2. Clone this repo
3. In `index.html`, replace POST_CLIENT_ITEM_ACCESS_TOKEN with your own post_client_item Rollbar access token
4. Open a terminal and cd into the directory where this repo is. Run `python -m SimpleHTTPServer 8080`
5. Open another terminal window and cd into the directory where this repo is. Run `python -m SimpleHTTPServer 8081`
6. In your browser, navigate to `http://localhost:8080`.
7. Click the buttons and watch what happens in the console.
