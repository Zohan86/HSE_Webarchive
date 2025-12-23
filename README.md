# HSE_Webarchive
Домашнее задание по предмету Веб архивация
Этот репозиторий содержит коллекцию веб-архивов созданную с использованием инструмента wpull для загрузки файлов, описание метаданных полученное с помощью metawarc, а также результат анализа коллекции с помощью ресурса ArchiveReady по метрикам CLEAR.

Краткое описание
В данной работе мы сохраняли архивы сайтов для получения практики архивации сайтов, понимания механик и инструментов.

В коллекцию входят:

https://disk.yandex.ru/d/FZhLFJblGJE_VA - icmos.ru - информ центр правительства Москвы (из примера на лекции)

https://disk.yandex.ru/d/FZhLFJblGJE_VA - klnran.eu - комиссия по борьбе с лженаукой (из примера) 

https://disk.yandex.ru/d/FZhLFJblGJE_VA - seledkagazeta.ru -  газета о культурной жизни города, о людях, живущих в нём, и известных писателях, режиссёрах, музыкантах.

https://disk.yandex.ru/d/FZhLFJblGJE_VA - vostokoriens.ru - журнал Восток. Афро-азиатские общества: история и современность

https://disk.yandex.ru/d/FZhLFJblGJE_VA - госавтоинспекция.рф - сайт ГАИ 

Метод и технология
В данной работе использовали несколько инструментов для создания полноценной коллекции веб-архивов.

Для сохранения архива воспользовались wpull. Этот инструмент представляет из себя утилиту командной строки а также библиотеку Python и позволяет загружать архивы с широким выбором заданных параметром (глубина рекурсии, timeout, метаданные архивирующего лица итд). В данной работе для загрузки нескольких архивов последовательно, мы воспользовались wpull через Python-скрипт массовой загрузки

Воспроизвести полученные архивы удалось с помощью сервиса ReplayWeb.page,

Оценка архивируемости сайтов проводилось на сервисе сервиса ArchiveReady.
Пример оценки архивируемости icmos.ru:
Overall Rating
69%

Results
Web Archivability Facet
Rating
Accessibility
45%
Cohesion
60%
Metadata
80%
Standards Compliance
91%
About the method
Web archivability can be measured from several perspectives. Here, we have called these perspectives Archivability Facets. Their selection and calculation is based on information gathered from the target website combined with an evaluation of the website's compliance with recognised practices in digital curation (e.g. using adopted standards, validating formats, and assigning metadata). For more information, pleace check the following publications:
Banos V., Manolopoulos Y., Web Content Management Systems Archivability, ADBIS 2015, BIB. (http://dev.archiveready.com/bibtex-wcms.txt)
Banos V., Manolopoulos Y.: A quantitative approach to evaluate Website Archivability using the CLEAR+ method, International Journal on Digital Libraries, 2015, Springer Link (http://link.springer.com/article/10.1007/s00799-015-0144-4?sa_campaign=email/event/articleAuthor/onlineFirst) · BIB. (https://archiveready.com/bibtex-springer.txt)
Banos V., Kim Y., Ross S., Manolopoulos Y.: CLEAR: a credible method to evaluate website archivability, iPRES 2013, PDF (http://purl.pt/24107/1/iPres2013_PDF/CLEAR%20a%20credible%20method%20to%20evaluate%20website%20archivability.pdf) · BIB. (https://archiveready.com/bibtex.txt)





Итог работы:
сформировал архивы различных сайтов, научился работать с инструментами для архивирования и воспроизведения сайтов. 



