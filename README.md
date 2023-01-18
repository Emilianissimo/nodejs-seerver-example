# Node JS simple example (JSON/ HTML)

Source code from here: <a href="https://www.digitalocean.com/community/tutorials/how-to-create-a-web-server-in-node-js-with-the-http-module">https://www.digitalocean.com/community/tutorials/how-to-create-a-web-server-in-node-js-with-the-http-module</a>

Implemented two index files to run them, just:

```bash
node <index_file_name>
```

### Notes
The same implementation (as well) as PHP server, or Python, GO, etc.

We just creating some bootstrap file, which uses our (or not) http library to control incoming requests (no need for PHP, 'cause nobody runs PHP as a balancer). Setting up host + port by balancer, getting requests, switching between route matching (could be regex for params) and sending end response. Between matching and ending, we can implement our data-working-solid-based-repository-model-whatever-your-framework-uses-crap-stuff.
