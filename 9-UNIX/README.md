#UNIX

<br/>
<table><thread><tr>
    <th>9. UNIX </th>
    <th> Explain</th>
  </tr></thread><tbody>

<tr>
    <th> Basic commands </th>
    <td>
        <b>< </b>: Read
        <br/>
        <b>> </b> : Write
        <br/>
        <b>|</b> Pipe. This takes stdOut from the previous proces and uses it in stdIn of the next process. Pipes, in the command line at least, are unidirectional.
        <br/>
        <b>grep</b>: grep "what you're looking for" inhere.java => This will then print every instance of "what you're looking for"
        <br/>
        <b>chmod</b>: chmod xyz thisfile => (where 0
        <=x , y, z <=6 ) This allows you to change the access file permissions. X represents the owner, Y is the group, and Z is other; where each digit represents 3 bits. In other words, 6 represents 110 or 7 representing 111. Each bit represents a permission: Read/View ||| Write/Edit ||| Execute. So if we do "chomd 666 myfolder"=> we have given Read/Write permissions to the owner, group, and other.
            <br/>
            <hr/>
            <b>Writing to a file via cmnd line</b>: echo 'Hello, World. ' > foo.txt
            <br/>
            <b><u>Std</u></b>
            <br/><b>StdIn</b>: 0
            <br/><b>StdOut</b>: 1
            <br/><b>StdErr</b>: 2
            <hr/>
            <b><u>More UNIX</u></b>
            <br/><b>Terminal</b>: Text input and ouput environment.
            <br/><b>Shell</b>: Command line interpretator
            <br/><b>Console</b>: "Physical" terminal
            <hr/>
            <br/><b>Coping a file</b>: cp filledfile.js copyOntoHere.js
            <br/> If the copyOntoHere.js DNE, it will automatically be created for you.
            <br/>
            <pre><code>  echo 'var i = 10;' > dummy.js
  cp dummy.js cloneDummy.js</code></pre>
  <hr/>
  <b>If we have a 32-bit machine, what's the largest # possible?</b>
  <br/>
  <b>Answer</b>:
  <pre>
  Logic:
   2-bit => 11 => The largest possible binary number we can get is 3.
   3-bit => 111 => Largest possible is 7.
   There is a pattern which is: [(X-bit) * 2 ] - 1 = = = 2<sup>x</sup> - 1


  </pre>
    </td>
</tr>
