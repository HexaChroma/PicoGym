# login (300+ solved webchal)
## by hexachroma

1. Clicking the link brings us to a login page!
> ![](docs/login.png)

2. lets try the stupid `admin:admin` and see if it works
> ![](docs/beingstupid.png)

3. We get an error. *surprised picachu face*
> ![](docs/pewdiepie.png)

4. Stuck? Aww poor thing.. Why don't you see what's under the hood?
> use ctrl+u to read **sourcecode** or `curl -s <uri>`
> ![](docs/kekw.png)

5. It loads JS? is this some kind of rest application? or something stupid?
> lets intercept our request using foxy proxy to localhost:8080
> ![](docs/nothing.png)

6. Download index.js with `curl -s <url/index.js> -o indexjs.out`
> ![](docs/creds.png)

7. b64decode password from index.js

***done***