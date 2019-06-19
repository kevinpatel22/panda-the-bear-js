
0. document.querySelector('.profile-image').src = "https://placebear.com/g/300/400";

1. document.querySelector('.photography').src = "images/self-portrait-snowbg.jpg";

2. document.querySelector('h1 .highlight').innerText = "Kevin Patel";

3. document.querySelector('#employment .info-title').innerText = 'Work';

4. document.querySelector('body') .style.backgroundColor = 'black';

5. var highlights = document.querySelectorAll('.highlight');
for (i = 0; i < highlights.length; i++) {
    highlights[i].style.backgroundColor = 'gold';
}

6. document.querySelector('h1').style.fontFamily = "monospace";

7. document.querySelectorAll('.action-container .action-icon-bg').forEach(element => element.style.backgroundColor = 'blue')

8. document.querySelector('name').placeholder = 'identify yourself'

9. document.querySelector('#message').placeholder = 'state your business'

10. document.querySelector('#name').value = 'your nemesis'

11. document.querySelector('#name').value = 'koalathebear@gmail.com'

12. document.querySelector('#submit').value = 'En grade!'

13. document.querySelector('#submit').disabled = true

14. document.querySelector('.bio-info').parentNode.removeChild(document.querySelector('.bio-info'));