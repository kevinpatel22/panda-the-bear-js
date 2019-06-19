
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

7. document.querySelectorAll('.action-container .action-icon-bg').forEach(element => element.style.backgroundColor = 'blue');

8. document.querySelector('name').placeholder = 'identify yourself';

9. document.querySelector('#message').placeholder = 'state your business';

10. document.querySelector('#name').value = 'your nemesis';

11. document.querySelector('#name').value = 'koalathebear@gmail.com';

12. document.querySelector('#submit').value = 'En grade!';

13. document.querySelector('#submit').disabled = true;

14. document.querySelector('.bio-info').parentNode.removeChild(document.querySelector('.bio-info'));


<!-- PART 2 -->

1. const skilltt = document.querySelector('#time-travel').parentNode;
skilltt.parentNode.removeChild(skilltt);

1. img = document.querySelector('#right-image img').cloneNode();
document.querySelector('.portfolio-container').appendChild(img);

2.  for (i = 0; i < 10; i++) { 
        img = document.querySelector('#right-image img').cloneNode();
        document.querySelector('.portfolio-container').appendChild(img);
    }

3. const listItem = document.createElement('li'); 
const leftSpan = document.createElement('span');
var lastUpdated = document.createTextNode('Page last updated on');
leftSpan.appendChild(lastUpdated);
listItem.appendChild(leftSpan);
const rightSpan = document.createElement('span');
let date = document.createTextNode(new Date);
rightSpan.appendChild(date);
listItem.appendChild(rightSpan);
const sidebar = document.querySelector('.bio-info');
sidebar.appendChild(listItem);




