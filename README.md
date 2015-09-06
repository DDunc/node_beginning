Some of my favorite errors:

1)	throw new assert.AssertionError({ //because I didn't write the argument as a string

2)	fs.createReadStream("/tmp/test.png").pipe(response);
	^
ReferenceError: fs is not defined //because I didn't require fs in the handlers file

3) No request handler found for /show //because I didn't give the handler a "/show" key


