---


---

<h2 id="лабораторна-робота-№2"><strong>Лабораторна робота №2</strong></h2>
<ol>
<li>Створено граф G={7,12}<br>
матриця суміжності графу:<br>
0, 1, 0, 0, 0, 0, 1,<br>
1, 0, 1, 0, 0, 0, 0,<br>
0, 1, 0, 1, 0, 0, 0,<br>
0, 0, 1, 0, 0, 1, 0,<br>
0, 0, 0, 0, 0, 1, 0,<br>
0, 0, 0, 1, 1, 0, 1,<br>
1, 0, 0, 0, 0, 1, 0,</li>
</ol>
<p><img src="https://i.ibb.co/9qHTwVp/1.png" alt="граф"></p>
<p><strong>i.</strong>  В даному графі ізольовані вершини або незв’язні компоненти відсутні. Для того щоб отримати ізольовану вершину потрібно видалити ребра які зв’язують вершину 5 з іншими вершинами.<br>
<strong>ii</strong>. Вершини типу глухий кут у графі відсутні.<br>
<strong>iii.</strong> Цикл Гамільтона присутній, послідовність вершин наступна: 0⇒1⇒2⇒3⇒4⇒5⇒6⇒0<br>
<strong>iv.</strong> Цикл Ейлера відсутній. Для того щоб реалізувати цикл Ейлера потрібно змінити розташування вершин і видалити зайві ребра. наприклад, таким чином:<img src="https://i.ibb.co/R0S32hH/3111111111111.png" alt="enter image description here"><br>
Цикл Ейлера для даного графа: 0⇒1⇒2⇒3⇒4⇒5⇒6⇒0<br>
<strong>v.</strong> Оберний граф має такий вигляд:<img src="https://i.ibb.co/jgTdbtH/999999999999999999.png" alt="enter image description here"><br>
2. Створено граф,  G={7,15}<img src="https://i.ibb.co/mJ4TCjQ/22222222222222222222222.png" alt="enter image description here"><br>
Його матриця суміжності:<br>
0, 1, 1, 1, 1, 0, 0,<br>
1, 0, 1, 1, 0, 0, 0,<br>
1, 1, 0, 0, 1, 1, 1,<br>
1, 1, 0, 0, 1, 1, 1,<br>
1, 0, 1, 1, 0, 1, 1,<br>
0, 0, 1, 1, 1, 0, 1,<br>
0, 0, 1, 1, 1, 1, 0,</p>
<p>**i.**якщо циклічно зсунуту вправо 2 стовпці у матриці суміжностей, то граф буде виглядати наступним чином:<br>
<img src="https://i.ibb.co/47pqp87/666666666666666666666666666.png" alt="enter image description here"><br>
матриця суміжності:<br>
0, 0, 0, 1, 1, 1, 1,<br>
0, 0, 1, 0, 1, 1, 0,<br>
1, 1, 1, 1, 0, 0, 1,<br>
1, 1, 1, 1, 0, 0, 1,<br>
1, 1, 1, 0, 1, 1, 0,<br>
0, 1, 0, 0, 1, 1, 1,<br>
1, 0, 0, 0, 1, 1, 1,<br>
<strong>ii.</strong> а) Якщо всі елементи над діагоналлю перетворити в 1, граф виглядатиме так:<br>
<img src="https://i.ibb.co/FJz8pv8/77777777777777.png" alt="enter image description here"><br>
матриця суміжності:<br>
0, 1, 1, 1, 1, 1, 1,<br>
1, 0, 1, 1, 1, 1, 1,<br>
1, 1, 0, 1, 1, 1, 1,<br>
1, 1, 0, 0, 1, 1, 1,<br>
1, 0, 1, 1, 0, 1, 1,<br>
0, 0, 1, 1, 1, 0, 1,<br>
0, 0, 1, 1, 1, 1, 0,<br>
<em>б)</em> Якщо всі елементи під діагоналлю перетворити в 0, тоді граф виглядатиме наступним чином:<br>
<img src="https://i.ibb.co/x7VG41S/8888888888888888888888.png" alt="enter image description here"><br>
матриця суміжності:<br>
0, 1, 1, 1, 1, 0, 0,<br>
0, 0, 1, 1, 0, 0, 0,<br>
0, 0, 0, 0, 1, 1, 1,<br>
0, 0, 0, 0, 1, 1, 1,<br>
0, 0, 0, 0, 0, 1, 1,<br>
0, 0, 0, 0, 0, 0, 1,<br>
0, 0, 0, 0, 0, 0, 0,<br>
<strong>3.</strong> граф <code>G={5,10}</code>:<br>
<img src="https://i.ibb.co/JdsVLBx/1.png" alt="enter image description here"><br>
матриця відповідностей (інцендентності):</p>
<p>1, 0, 0, 0, 1, 0, 1, 1, 0<br>
-1, 1, 0, 0, 0, 1, 0, 0, 0<br>
0, -1, -1, 0, 0, 0, 0, 1, 1<br>
0, 0, 0, 1, 1, 1, 0, 0, 1<br>
0, 0, 1, 1, 0, 0, 1, 0, 0</p>
<p><strong>i.</strong> 1.  Щоб з матриці відповідностей визначити ступінь вершини, потрібно просумувати кількість одиниць в рядку матриці.</p>
<p><strong>4.</strong> <strong>i.</strong> Граф G:<br>
<img src="https://i.ibb.co/ZSbJ3s3/G.png" alt="enter image description here"><br>
матриця суміжності графу G:<br>
0, 0, 0, 0, 0, 0, 1,<br>
0, 0, 1, 0, 0, 0, 1,<br>
0, 0, 0, 1, 0, 0, 1,<br>
0, 0, 0, 0, 0, 0, 1,<br>
1, 0, 0, 0, 0, 1, 0,<br>
1, 0, 0, 0, 0, 0, 1,<br>
0, 0, 0, 0, 0, 0, 0,</p>
<p>Граф M:<br>
<img src="https://i.ibb.co/ZSbJ3s3/G.png" alt="enter image description here"><br>
матриця суміжності графу M:<br>
<img src="https://i.ibb.co/rdZx9kn/M.png" alt="enter image description here"><br>
<strong>ii.</strong> Граф G є орієнтованим, а граф M - нероієнтованим.<br>
<strong>iii.</strong> граф G: V = 7, E = 12; граф M: V = 6, E = 16;<br>
<strong>iv.</strong>найбільшу ступінь (2) у графі G мають вершини 3 та 6. У графі M - друга та п’ята вершини  мають найвищий ступінь 4.<br>
<strong>v.</strong> ексцентриситети вершин графу G(вершина:ексцентриситет):<br>
1:1<br>
2:3<br>
3:2<br>
4:1<br>
5:1<br>
6:1<br>
7:0<br>
ексцентриситети вершин графу M(вершина:ексцентриситет):<br>
1:4<br>
2:4<br>
3:0<br>
4:4<br>
5:4<br>
6:4<br>
<strong>vi.</strong> Радіус графа G: 1 (1⇒7); граф M не є зв’зним, тому неможливо визначити його радіус.<br>
<strong>vii.</strong>Діаметер графа G: 2 (2⇒3⇒4); граф M не є зв’зним, тому неможливо визначити його діаметер.<br>
<strong>viii.</strong>  граф G і М не мають елементарних циклів.<br>
<strong>ix.</strong> граф  G не містять ізольованих вершин,  у графі М третя вершина є ізольованою.<br>
<strong>x.</strong> Граф  G зміниться наступним чином:<br>
<img src="https://i.ibb.co/5jqs7kW/GT.png" alt="enter image description here"><br>
Граф  M зміниться наступним чином:<br>
<img src="https://i.ibb.co/7j843Sk/MT.png" alt="enter image description here"></p>

