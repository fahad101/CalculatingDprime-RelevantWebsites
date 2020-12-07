# CalculatingDprime-RelevantWebsites

Determine correct way to Calculate d prime in Yes-No recognition test compared to d prime in 2-Alternative Forced-choice test.

https://cran.r-project.org/web/packages/psyphy/psyphy.pdf
https://www.frontiersin.org/articles/10.3389/fpsyg.2020.00073/full
https://www.rdocumentation.org/packages/psycho/versions/0.5.0/topics/dprime

https://rstudio-pubs-static.s3.amazonaws.com/371840_5694e490af85424eb7e7f3ae721cd67d.html

http://phonetics.linguistics.ucla.edu/facilities/statistics/dprime.htm

http://phonetics.linguistics.ucla.edu/facilities/statistics/dprime.htm

https://memory.psych.mun.ca/models/recognition/2afc.shtml

http://www.mbfys.ru.nl/~robvdw/DGCN22/PRACTICUM_2011/LABS_2011/ALTERNATIVE_LABS/Lesson_8.html

https://brain.mcmaster.ca/SDT/dprime.html

https://www.rdocumentation.org/packages/psycho/versions/0.5.0/topics/dprime

The way to fix this is as follows:

Calculate a minimum and maximum score for your data.

It is possible that a respondent detects every signal, giving a hit rate of H = 1.00, or a respondent might make no false alarms giving FA = 0. A right-tail p value of 0 corresponds to z = infinity while a p value of 1 corresponds to z =negative infinity. This poses a problem for computing d’!

A conventional adjustment is to set the minimum p = 1/N where N is the number of trials used in the calculation of p. We set the maximum value for p = (N-1)/N.

http://www.mbfys.ru.nl/~robvdw/DGCN22/PRACTICUM_2011/LABS_2011/ALTERNATIVE_LABS/Lesson_9.html

http://www.mbfys.ru.nl/~robvdw/DGCN22/PRACTICUM_2011/LABS_2011/ALTERNATIVE_LABS/

https://www.rdocumentation.org/packages/verification/versions/1.42/topics/roc.plot

https://yonelinas.faculty.ucdavis.edu/roc-analysis/

To correct the #NUM error, just change the participants perfect hit rate
from 1.000 to 0.995 and/or any individual false alarm rate of 0.000 to
.005. I would also double check you calculation of HR-FAR for the CWs
and NCWs of the older participants, as I do not think they are all
correct.
