Download Link: https://assignmentchef.com/product/solved-blockchain-homework-3
<br>
In this lab, you will implement the ScroogeCoin cryptocurrency. You will act as Scrooge and verify transactions sent to you by users and add them to your ledger.

A few JUnit test cases have been given to you as sanity checks on your code, but the grading will be based different test cases. You should invest time in developing your own test cases.

In this lab, you will implement a ScroogeCoin application server.

Assume the following about the server:

<ol>

 <li>Has the URL is https://scroogecoin.com.</li>

 <li>Only accepts connections over HTTPS.</li>

 <li>Has a valid SSL certificate.</li>

 <li>Does not authenticate any users, include Scrooge.</li>

 <li>Scrooge is the only person in control of the server.</li>

</ol>

These assumptions enable users to trust that any response they receive from the server is authorized by Scrooge. However, because the server does not authenticate users, your implementation will need to rely on digital signatures to process transactions securely. Scrooge runs the server and then submits transactions to the server through a web browser, like any other user.

Implement the following methods per the comments in the DefaultScroogeServer.java class file.

DefaultScroogeServer.init(KeyPair)

DefaultScroogeServer.epochHandler(List&lt;Transaction&gt;)

DefaultScroogeServer.isValid(Transaction)

DefaultScroogeServer.getUTXOs()