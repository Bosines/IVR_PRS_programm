# Тумаков Никита - "Разработка программы для курса физиологии регуляторных систем"
# Пользовательские сценарии

### Группа: 11 - Е - 1
### Электронная почта: mister.ti199@gmail.com
### VK: www.vk.com/Bosines


### [ Сценарий 1 - Осмотр мозга ]

1.  На экране появляется окно с 3д моделью мозга, подписями, слайдером, иконкой меню и кнопкой, вызывающей на экран кнопку выбора среза, кнопки выбора медиаторов, кнопку выключения надписей 
2.  Пока зажата кнопка вращения мозга (назначается пользователем), пользователь может вращать мозг движением мыши
3.  При вращении колёсика мышки или перемещении ручки слайдера мозг приближается или отдаляется
4.  Если мозг повёрнут частью, сопровождающейся подписью, на экране появляется подпись
5.  При нажатии на кнопку вызова меню (назначается пользователем), либо же на иконку меню, запускается сценарий 2
6.  При нажатии на кнопку выбора среза запускается сценарий 5
7.  При нажатии на кнопку выбора медиаторов открывается изображение, показывающее пути движения медиаторов
8.  При нажатии на кнопку выключения надписей надписи на модели становятся невидимыми
9.  При повторном нажатии на кнопку выключения надписей надписи на модели становятся видимыми
10. При нажатии на подпись к участку мозга запускается сценарий 4 с соответствующими слайдами

### [ Сценарий 2 - Открытие меню с выбором слайда ]

1. На экране появляются окно меню, содержащее список тем, и кнопка настроек
2. При нажатии на определённую тему появляется окно с выбором подтем
3. При нажатии на другую тему появляется окно с другими подтемами
4. При нажатии на подтему запускается сценарий 4 со слайдами на выбранную подтему
5. При нажатии на подтему, относящуюся к смешанным подтемам, запускается сценарий 3
5. При нажатии на клавишу вызова меню, либо же на иконку меню, окно меню закрывается
6. При нажатии на кнопку 'настройки' запускается сценарий 6

### [ Сценарий 3 - Переключение в смешанный режим презентации и 3д модели ]

1. Появляется окно с слайдами по выбранной теме или выбранному участку мозга, кнопками 'назад', 'вперёд', 'меню', 3д модель, повёрнутая изучаемой частью
2. При нажатии на стрелочки на клавиатуре или на кнопки 'вперёд' и 'назад', слайды, относящиеся к данному разделу, переключаются. При этом мозг поворачивается в соответствии с контентом слайда
5. Если открытый слайд содержит кнопку с дополнительной информацией, при нажатии на неё открывается окно с дополнительной информацией
6. Если открытый слайд содержит ссылку на участок мозга, при нажатии на неё запускается сценарий 3
7. Если открытый слайд содержит ссылку на другой слайд, при нажатии на неё слайд переключается
8. Если открытый слайд содержит ссылку на медиатор, при нажатии на неё запускается сценарий 1 и отображается медиатор
9. При нажатии на клавишу ESC на клавиатуре запускается сценарий 1

### [ Сценарий 4 - Переключение в режим презентации ]

1. Появляется окно с слайдами по выбранной теме или выбранному участку мозга, кнопками 'назад', 'вперёд', 'меню'
2. При нажатии на клавиши переключения слайдов или на кнопки 'вперёд' и 'назад' на экране, слайды, относящиеся к данному разделу, переключаются
3. Если только что открытый слайд содержит анимацию, проигрывается анимация
4. Если открытый слайд содержит анимацию, при нажатии на часть слайда, содержащую анимацию, анимация останавливается или запускается снова при повторном нажатии
5. Если открытый слайд содержит кнопку с дополнительной информацией, при нажатии на неё открывается окно с дополнительной информацией
6. Если открытый слайд содержит ссылку на участок мозга, при нажатии на неё запускается сценарий 3
7. Если открытый слайд содержит ссылку на другой слайд, при нажатии на неё слайд переключается
8. Если открытый слайд содержит ссылку на медиатор, при нажатии на неё запускается сценарий 1 и отображается медиатор
9. При нажатии на клавишу ESC на клавиатуре запускается сценарий 1

### [ Сценарий 5 - Переключение в режим среза ]

1. Программа переключается в режим среза
2. Часть модели становится невидимой, открывая внутреннюю часть
3. Подписи меняются на соответствующие срезу
4. При нажатии на кнопку выключения надписей надписи на модели становятся невидимыми
5. При повторном нажатии на кнопку выключения надписей надписи на модели становятся видимыми
6. При нажатии на подпись к участку мозга запускается сценарий 4 с соответствующими слайдами
7. При нажатии на клавишу ESC на клавиатуре запускается сценарий 1

### [ Сценарий 6 - Переключение в режим настроек ]

1. Появляется окно с настройками приложения
2. Пользователь может изменить кнопки на клавиатуре, используемые для вызова меню, вращения мозга и вызова дополнительного меню
3. Пользователь может включить или отключить отображение анимации в слайдах
4. Пользователь может изменить чувствительность мыши
5. При нажатии на кнопку 'назад' запускается сценарий 1
