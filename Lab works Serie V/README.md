# Lab works, Serie IV
### [Task](http://www.machinelearning.ru/wiki/index.php?title=Математические_методы_прогнозирования_%28лекции%2C_А.В._Грабовой%2C_В.В._Стрижов%29/Осень_2021#Lab_works.2C_Serie_V)
### [Colab version](https://colab.research.google.com/drive/1e3v43tbnBT10QTcb_waVkYpcJ3zcpcFC?usp=sharing)

The goal of the lab set is to join several, possible simple modules using joint efforts and information exchange. The following modules make the system work. PLS scheme

### Lab 0
* Make the documented demo of the system. List to run all possible models. Make an example of the most interesting models (Linear, Autoencoders, Neur-ODE, Tensor, Graph).
* In: All labs, ### Lab 4,5
* Out: github.io page with examples

### Lab 1
* Load data and put the data to PLS. Two sets of data: synthetic and real (X is time series times sensors, Y is time series times 3D coordinates)
* In: no
* Out: the formats for X, Y, U, V

### Lab 2
Make a set of the error functions. The reconstruction of (X, X), of (Y,Y), and of (Y, X)
* In: lab 1
* Out: Four functions Qall, QXX, QYY, QXY

### Lab 3
* Check the admissibility of any given module in the system. Run the system in all variants
* In: All Labs
* Out: it works in the system, yes/no

### Lab 4
* Make the simplest system, linear transformations
* In: Lab 1, Lab 2
* Out: The shell with .predict, .fit stubs, which include interfaces to the models XX, YY, XY

### Lab 5
* Select an optimisation algorithm from the set to optimise error functions
* In: Lab 2, Lab 3
* Out: The optimal parameters for the system and predictions

### Lab 6
* Plot the predictions and error analysis
* In: Lab 5
* Out: Series of plots

### Lab 7 Make YY Neur-ODE model
* In: Lab 5
* Out: Series of plots

### Lab 8
* Make XX, YY, stack-auto-encoder model
* In: Lab 5
* Out: The tuned model and forecast

### Lab 9
* Make XX, tensor decomposition model
* In: Lab 5
* Out: The tuned model and forecast

### Lab 10
* Make XX Graph convolution model
* In: Lab 5
* Out: The tuned model and forecast

### Lab 11
Make XX Graph LSTM model
* In: Lab 5
* Out: The tuned model and forecast

### Lab 12
* Make XX Graph GRAND model
* In: Lab 5
* Out: The tuned model and forecast


## References
1. neurotycho.org
2. Яушев Ф.Ю., Исаченко Р.В., Стрижов В.В. Модели согласования скрытого пространства в задаче прогнозирования // Системы и средства информатики, 2021, 31(1) : 4-16.
3. Motrenko A.P., Strijov V.V. Multi-way feature selection for ECoG-based brain-computer interface // Expert Systems with Applications, 2018, 114(30) : 402-413.
4. Grabovoy A.V., Strijov V.V. Quasi-periodic time series clustering for human activity recognition // Lobachevskii Journal of Mathematics, 2020, 41 : 333-339.
5. Роман Владимирович Исаченко Снижение размерности пространства в задачах декодирования сигналов git, автореферат, презентация (PDF). 2021. МФТИ
6. Мотренко Анастасия Петровна. Выбор моделей прогнозирования мультикоррелирующих временных рядов, автореферат, презентация (PDF)
