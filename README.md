**Jacoco счетчики покрытия кода тестами**

# INSTRUCTION (уровень команд)
Счетчик рассчитывает покрытие инструкция байт-кода. Покрытие INSTRUCTION показывает, какие инструкции были выполнены, а какие пропущены. Этот показатель полностью независим от исходного форматирования кода. 

# BRANCH
Счетчик рассчитывает покрытие для всех инструкций-условных выражений (ветвей). Покрытие BRANCH  подсчитывает количество всех ветвей и определяет количество выполненных и пропущенных ветвей.
Есть три состояния для представления результатов покрытия:
* нет покрытия, все ветви не выполнены
* частичное покрытие, есть не выполняемые ветви
* полное покрытие, все ветви выполнены
 
# LINE
Счетчик рассчитывает покрытие отдельных строк кода. Покрытие LINE является полным, если выпонены все инструкции в строке.
Есть три состояния для представления результатоа покрытия:
* нет покрытия, се инструкции в этой строке не выполняются
* частичное покрытие, некоторые инструкции в этой строке выполнены
* полное покрытие, все инструкции в этой строке выполнены
