# hse_hw2_chip
## Васильева Дарья
#### В данной работе была взята клеточная линия A549 и гистоновая метка H3K27me3. 
#### Реплика 1 - ENCFF000AKW, реплика 2 - ENCFF000AKV, контроль - ENCFF000AHJ
#### Ссылка на гугл коллаб: https://colab.research.google.com/drive/1lqxAVauwgC0wRJMww57IaZ9nn_QVBd1x?usp=sharing
## FastQC для файла ENCFF000AKW
#### ![image](https://user-images.githubusercontent.com/114879123/220972710-48ef4aed-29a9-4c75-81b7-50ac410093f7.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220972276-bea418c8-11fc-49ae-acb2-639c7e90dad5.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220972833-e6980c1d-6a7b-40f3-8b86-64dd8b9b73d8.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220972907-1c149c7d-3810-439a-ac64-ec90c5214b6a.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220972993-65bb265a-be2d-41e0-9703-88831e1a94c1.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220973177-484420ba-7b31-4c3f-9014-1f89ae01ea59.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220973248-d944eaec-a3d9-4efd-90d7-19aa5667d63c.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220973359-0face456-493f-41d8-a3e6-dca02073be82.png)
## FastQC для файла ENCFF000AKV
#### ![image](https://user-images.githubusercontent.com/114879123/220974035-fb8ffe99-5ee4-43c8-996f-0fd249d4ceed.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220974260-6a0894f0-c904-4087-af99-f6988a0e80aa.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220975005-6569754e-45ae-415c-969d-00ea2d6a51bb.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220975052-1c803e04-11ff-48c4-8b38-66bf8eca8304.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220975152-9737165f-68aa-46bc-a373-bfb964569734.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220975252-092e45f6-79c2-496d-ac7c-8726f819924a.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220975323-0afe0a5c-316d-4ef9-b7fb-9b1814de077f.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220975434-d616c34c-0ee7-4502-b534-e664bbaca040.png)
## FastQC для файла ENCFF000AHJ
#### ![image](https://user-images.githubusercontent.com/114879123/220977141-6714a068-2027-44cf-8cb4-7b2fca936307.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220977227-d2de402c-dcbe-4e7e-8efb-1b17d6b1695a.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220977338-11b81798-967b-47a8-b52b-d31e8da08c57.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220977502-916854bb-48c6-45f9-9521-2c53ca17f721.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220977558-5365ce1b-04b5-4421-ab4e-68c4bd4b4d44.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220977622-94be85e3-50b0-46ad-b049-eda6e42e983a.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220977683-b52c426d-868d-4035-8cb7-df372485ad15.png)
#### ![image](https://user-images.githubusercontent.com/114879123/220977748-a0b09ffe-7fd8-46ec-9c57-1dd0fd77336c.png)
#### Так как качество ридов хорошее, то подрезание чтений не нужно
## Статистика по 3 образцам
  | Файл | Кол-во ридов в файле  | Кол-во ридов, выравнившихся уникально | Кол-во ридов, выравшнившихся не уникально | Кол-во ридов, не выравнившихся |
  | ENCFF000AKW | 34433746 | 1662770 (4.83%)  | 4254963 (12.36%)  | 28516013 (82.81%)  |
  | ENCFF000AKV | 33807036  | 1632319 (4.83%)  | 3979200 (11.77%)  | 28195517 (83.40%) |
  | ENCFF000AHJ | 38269770  | 1982850 (5.18%)  | 5596985 (14.63%)  | 30689935 (80.19%) |
## Диаграммы Венна о пересечении пиков
#### Ниже приведены диаграммы Венна. Как можно заметить, в каждом образце довольно мало пересечений, что может объясняться тем, что мы проводили выравниевание только на одну хромосому. Различия в количестве пересечений могут быть объяснены тем, что для ENCODE база данных более обширная и пики присутствуют для каждой хромосомы.
### Реплика ENCFF000AKW с ENCODE
![image](https://user-images.githubusercontent.com/114879123/221355905-8aeb1ed5-993a-41ed-b9b4-349e49df4a92.png)
### ENCODE с репликой ENCFF000AKW
![image](https://user-images.githubusercontent.com/114879123/221355944-b0ae0908-571c-47ba-a92e-83f820449c5c.png)
### Реплика ENCFF000AKV с ENCODE
![image](https://user-images.githubusercontent.com/114879123/221355951-d9b1a1bb-2c48-43c8-8e8a-8dbbc5c98b6d.png)
### ENCODE с репликой ENCFF000AKV
![image](https://user-images.githubusercontent.com/114879123/221355965-6c466e9a-2099-417c-a5df-3980f7bc3efa.png)



