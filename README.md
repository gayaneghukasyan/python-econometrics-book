# Python-ի գործիքակազմի կիրառությունը էկոնոմետրիկ վերլուծություններում

Ուսումնական ձեռնարկում ներկայացված են տվյալների վիճակագրական վերլուծության և ռեգրեսիոն մոդելավորման ժամանակակից մեթոդներն ու դրանց գործնական-էմպիրիկ կիրառությունները **Python** ծրագրավորման լեզվի միջավայրում:

Ռեգրեսիոն վերլուծությունների, էկոնոմետրիկ թեստերի և տվյալների վիզուալիզացիայի ծրագրային ապահովման նպատակով ձեռնարկում կիրառվել է Python լեզվի մասնագիտացված գործիքակազմը, մասնավորապես՝ **NumPy**, **Pandas**, **Matplotlib**, **Seaborn**, **SciPy** և **Statsmodels** գրադարանները: Գրքի յուրաքանչյուր բաժին պարունակում է առաջադրանքներ ինքնուրույն ուսումնասիրության համար։

---

### About the Book

This tutorial presents practical methods of statistical data analysis and regression modeling, along with their empirical applications using the **Python** programming language. 

For regression analysis, econometric testing, and data visualization, the textbook utilizes specialized Python tools, specifically the **NumPy**, **Pandas**, **Matplotlib**, **Seaborn**, **SciPy**, and **Statsmodels** libraries. Each section of the textbook contains tasks for self-study.

---

## 📂 Ռեպոզիտորիայի կառուցվածքը

Նյութերը դասակարգված են ըստ գրքի հիմնական մասերի և գլուխների: Յուրաքանչյուր թղթապանակում կգտնեք համապատասխան Jupyter Notebook (`.ipynb`) ֆայլերը։

### 📘 Բովանդակություն և Ծրագրային Կոդեր

* 📁 **[Մաս 1. Ծրագրային միջավայրի կարգավորումը և տվյալների ներմուծումը](notebooks/part1/)**  
  [![Open In Colab](https://google.com)](https://google.com)
  * Jupyter Notebook միջավայր, NumPy և Pandas գրադարաններ
  * CSV և Excel ֆայլերի ներբեռնում, միջազգային շտեմարաններ

* 📁 **[Մաս 2. Էկոնոմետրիկ տվյալների նախնական վերլուծությունը և վիզուալիզացիան](notebooks/part2/)**  
  [![Open In Colab](https://google.com)](https://google.com)
  * Նկարագրական վիճակագրություն
  * Գծապատկերներ (Matplotlib, Seaborn) և Կոռելյացիոն մատրիցներ

* 📁 **[Մաս 3. Ռեգրեսիոն մոդելների ծրագրավորումը և գնահատումը Statsmodels փաթեթով](notebooks/part3/)**  
  [![Open In Colab](https://google.com)](https://google.com)
  * Միագործոն և բազմագործոն գծային ռեգրեսիաներ
  * t-թեստ, F-թեստ, վստահության միջակայքեր, $R^2$ և $R_{adj}^2$

* 📁 **[Մաս 4. Մոդելների էկոնոմետրիկ ախտորոշումը և թեստավորումը](notebooks/part4/)**  
  [![Open In Colab](https://google.com)](https://google.com)
  * Նորմալ բաշխվածության ստուգում, Հետերոսկեդաստիկություն
  * Ավտոկոռելյացիա և Բազմակոլինեարություն (VIF թեստ)

* 📁 **[Մաս 5. Ոչ գծային կախվածությունների գնահատումը Python-ում](notebooks/part5/)**  
  [![Open In Colab](https://google.com)](https://google.com)
  * Լոգարիթմական մոդելներ (Log-Log, Lin-Log, Log-Lin)

* 📁 **[Մաս 6. Ֆիկտիվ փոփոխականների օգտագործումը ռեգրեսիոն մոդելում](notebooks/part6/)**  
  [![Open In Colab](https://google.com)](https://google.com)
  * Dummy փոփոխականների ներառում և ծրագրավորում

* 📁 **[data/](data/)** — Վերլուծությունների համար օգտագործված տվյալների բազաները։

---

## 🚀 Ինչպես սկսել (Installation)

Այս կոդերն իրականացնելու համար ձեր համակարգչում պետք է տեղադրված լինի **Anaconda** փաթեթը: Անհրաժեշտ գրադարանները կարող եք թարմացնել կամ տեղադրել Anaconda Prompt-ում հետևյալ հրամանով.

```bash
pip install numpy pandas matplotlib seaborn scipy statsmodels openpyxl
```
