### 1. 

Find the vector x if: (1, 2, 3, 0) + 2x = (-1, 0, 1, 6)

Розвʼязок:

$2\mathbf{x} = (-1, 0, 1, 6) - (1, 2, 3, 0) = (-2, -2, -2, 6)$  
$\mathbf{x} = \left(-1, -1, -1, 3\right)$

---

### 2. 

Find the vector C, if BC is three times shorter than AB.

$A = (-1, 5, 1)$  
$B = (2, 2, -2)$

Розвʼязок:  
Для знаходження вектору С ми можем скористатись наступними розрахунками.
Оскільки вектор С лежить на одній прямій з АВ, тоді:

$AB=B-A$  
$BC=1/3*AB$  
$BC=C-B$  
$C=BC+B$

Підставляєм відомі нам значення у формули і отримуєм:

$AB = B - A = (2, 2, -2) - (-1, 5, 1) = (3, -3, -3)$  
$BC = 1/3 * (3, -3, -3) = (1, -1, -1)$  
$C = (2, 2, -2) + (1, -1, -1) = (3, 1, -3)$

---

### 3.

A line comes through

$V1 = (1, 1, 3)$  
$V2 = (2, 0, -1)$

Does the point (1, 2, 1) belong to the given line?

Розвязок:  
Позначимо точку як $V3 = (1, 2, 1)$  
Якщо вектор AB помножити на скаляр, то його можна розтягнути до будь якого іншого вектора  
який буде лежати на цій же прямій (наприклад V3) починаючи від точки V1. 

Тому маємо наступне:

$V1V2 = V2-V1$  
$V3 = V1 + t * V1V2$
$V1V2 = (2, 0, -1) - (1, 1, 3) = (1, -1, 4)$

Знаходимо `t` підставивши дані у формулу 

* За x -координатою: $1 + t \cdot 1 = 1; t = 0$
* За y -координатою: $1 + t \cdot (-1) = 2; t = -1$
* За z -координатою: $3 + t \cdot (-4) = 1; t = 0,5$

Як бачимо дані суперечать один одному значить це неможливо і вектор V3 не лежить на прямій.

---

### 4.

Find vector x if vectors a, b, c, d are given and all
of them form a 5 pointed star like it is shown in
the picture.

Розвʼязок:  
Якщо зʼєднати вершини зірки векторами починаючи з вектора `x` то ми пройдемо коло і повернемось
в ту ж точку і сума векторів у такому разі дорівнюватиме 0

$a + b + c + d + x = 0$  
$x = -(a + b + c + d)$

---

### 5. 

We have got a set of vectors in the two-
dimensional vector space. All these vectors belong to
the line x2 = 2x1 shown as a dotted line. Does this
vector set form a liner space?

Розвʼязок:
Для вирішення даної задачі візьмемо наступні аксіоми для векторного простору 
і перевіримо чи рівняння прямої їх задовільняє

1. a + b = b + a - commutativity
2. a + (b + c) = (a + b) + c - associativity
3. a + 0 = a - identity element
4. for a, -a must exist, a + (-a) = 0
5. p(q a) = (p q)a - compatibility
6. 1 a = a - identity for scalar multiplication
7. ƛ ( a + b) = ƛa + ƛb - distributivity of scalar w.r.t. vectors
8. (m + n) a = ma + na - distributivity w.r.t field addition

---

1. a + b = b + a  
Якщо ми візьмемо два вектори на прямій, скажімо, $a = k_1 (1, 2)$ і $b = k_2 (1, 2)$,  
то:   
$a + b = k_1 (1, 2) + k_2 (1, 2) = (k_1 + k_2)(1, 2)$
$b + a = k_2 (1, 2) + k_1 (1, 2) = (k_2 + k_1)(1, 2)$  
$k_1,  k_2$ це скаляри.  
Отже a + b = b + a.


2. a + (b + c) = (a + b) + c  
Для векторів $a = k_1(1, 2), b = k_2(1, 2), c = k_3(1, 2)$:  
$a + (b + c) = k_1 (1, 2) + ((k_2 + k_3) (1, 2)) = (k_1 + k_2 + k_3)(1, 2)$
$(a + b) + c = ((k_1 + k_2) (1, 2)) + k_3 (1, 2) = (k_1 + k_2 + k_3)(1, 2)$  
$k_1,  k_2, k_3$ це скаляри.  
Отже, a + (b + c) = (a + b) + c


3. a + 0 = a  
Нульовим вектором на цій прямій є $0 = 0 \cdot (1, 2) = (0, 0)$,   
оскільки він задовольняє рівняння $x_2 = 2x_1$.
Для будь-якого вектора $a = k (1, 2)$:
$a + 0 = k (1, 2) + (0, 0) = k (1, 2) = a$


4. for a, -a must exist, a + (-a) = 0  
Для будь-якого вектора $a = k(1, 2)$, обернений елемент буде $-a = -k(1, 2)$.  
Тоді:  
$a + (-a) = k (1, 2) + (-k) (1, 2) = (k - k)(1, 2) = 0 \cdot (1, 2) = (0, 0)$

   
5. p(q a) = (p q)a  
Нехай $a = k(1, 2)$ і p, q — скаляри.  
Тоді:
$p(q a) = p(q \cdot k (1, 2)) = (pq \cdot k)(1, 2) = (pq) a$


6. 1 a = a  
Для будь-якого вектора  $a = k (1, 2)$:  
$1 \cdot a = 1 \cdot (k (1, 2)) = k (1, 2) = a$


7. ƛ ( a + b) = ƛa + ƛb  
Нехай $a = k_1(1, 2)$ і $b = k_2(1, 2)$,   
Тоді:  
$\lambda (a + b) = \lambda ((k_1 + k_2)(1, 2)) = (\lambda (k_1 + k_2))(1, 2)$  
$\lambda a + \lambda b = (\lambda k_1)(1, 2) + (\lambda k_2)(1, 2) = (\lambda (k_1 + k_2))(1, 2)$  
Отже,  ƛ ( a + b) = ƛa + ƛb.


8. (m + n) a = ma + na  
Нехай $a = k (1, 2)$  
Тоді:  
$(m + n) a = (m + n) k (1, 2) = (mk + nk)(1, 2)$
$ma + na = (mk)(1, 2) + (nk)(1, 2) = (mk + nk)(1, 2)$  
Отже, $(m + n) a = ma + na$ 

---
Множина векторів на прямій  x_2 = 2x_1  виконує всі 8 аксіом векторного простору, отже, вона дійсно утворює лінійний простір.