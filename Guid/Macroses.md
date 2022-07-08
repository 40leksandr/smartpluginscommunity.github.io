## Описание макро команд

-------------------------
* [Макросы модели](#Макросы-модели)
* [Макросы чертежа](#Макросы-чертежа)
-------------------------

### Макросы модели

| Команда | Описание |
|:-|:-|
| akit.Callback("acmdZoomToSelected", "", "View_01 window_1");          | Зумирование объекта в модели, где View_01 - вид из списка "выбранных" |
| akit.Callback("acmdHideUnselectedObjects", "", "View_01 window_1");   | Скрытие невыделенных объектов, где View_01 - вид из списка "выбранных" |
| akit.Callback("acmdHideSelectedObjects", "", "View_01 window_1");     | Скрытие выделенных объектов, где View_01 - вид из списка "выбранных" |
| akit.PushButton("dia_draw_select_parts", "Drawing_selection");        | Выбираем детали в модели по выбраным чертежам ("Select objects" в Списке чертежей) |
| akit.Callback("gdr_menu_select_active_draw", "", "main_frame");       | Делает активным окно "Список чертежей" |
| akit.TableSelect("Drawing_selection", "dia_draw_select_list", i);     | Выбирает активным чертеж с номером i в текущем списке отображаемых чертежей |

-------------------------

### Макросы чертежа

| Команда | Описание |
|:-|:-|
| akit.Callback("acmd_display_selected_drawing_object_dialog", "", "main_frame");     | Вызывает окно свойств вида |
| akit.PushButton("view_modify", "view_dial");                                        | Изменяет свойства вида |
