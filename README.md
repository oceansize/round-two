# Challenge #2, should you choose to accept...

The Internet Chuck Norris Database has an open public API. The endpoint is here:

http://api.icndb.com/jokes/:id

where :id is a 3-digit number corresponding to a joke, or "random".

Your task is to build a Ruby wrapper for the Chuck Norris API that does the following:

1. Makes a GET request to the endpoint, either to a random joke or specific joke. The method should be robust -- it should work for any ID passed in.
2. Parses the JSON object and extracts the content of the joke as a string
3. Replaces "Chuck Norris" with a different string passed in.

The method call should look something like this:

RubyWrapper.chucknorrisify(300, "Mihai")
=> "Mihai eats steak for every single meal. Most times he forgets to kill the cow."

You can use any Ruby gems or libraries you wish.

### Tips

Try to take a test-driven approach - having a spec file is necessary to pass the challenge.

Submissions will be evaluated on the basis of well-written tests, clean + readable code, and adherence to SOLID principles.

When your 15 minutes is up, push your solution to Github and Hipchat the repo link to the Codejam room.