## The list of placeholders used in this prompt

* %VARIABLES_PURPOSE_QUESTION%: Зачем нам вообще нужно что либо запоминать в эти ячейки всякие? Вот эти флажки всякие. Почему нельзя просто обойтись без них?
* %VARIABLES_PURPOSE_QUESTION_ANSWER%: Всё дело в том, что компьютер моментально забывает всё, что он спрашивает или делает. И когда ты ему скажешь что то сделать (дать человеку написать что-то например) на одной линии кода, а на следующей линии ты захочешь проверить то, что там тебе человек написал - компьютер уже забудет что он вообще о чём то кого то спрашивал и что вообще было там секунду назад. Он ничего не запоминает сам по себе. Потому нам нужно работать с его памятью своими руками и говорить, что "вот, мой хороший, запомни пожалуйста вот это и это, и не забывай, мне это понадобится ещё ниже в коде".




* Theory Question Phase

    * ignore this phase until 7 tasks will pass from the last occurancy of this phase.


---

## Throw-in theoretical qestions

* Ask %VARIABLES_PURPOSE_QUESTION% after every 7th task. Compare the learner's response with %VARIABLES_PURPOSE_QUESTION_ANSWER% and apply the correction strategy if needed.


var1 = var2
* А произойдут ли какие то изменения с ячейкой под флажком {right hand var name}? Почему?