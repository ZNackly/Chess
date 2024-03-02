                                                                    **CHESS GAME**

FEN (нотация Форсайта-Эдвардса) - это стандартная нотация, используемая для представления определенной позиции на шахматной доске. Она предоставляет краткий и понятный человеку способ описания размещения шахматных фигур на доске, а также другую важную информацию о позиции. Вот как работает нотация FEN:

Строка FEN состоит из шести полей, разделенных пробелами:

1. **Расположение фигур (8 рангов)**: Это поле представляет позиции фигур на доске. Каждый ранг представлен серией символов, где:
- `K` представляет белого короля.
- `Q` представляет белую королеву.
- `R` представляет белую ладью.
- `B` представляет белого слона.
- `N` представляет белого коня.
- `P` представляет белую пешку.
- `k` представляет черного короля.
- `q` представляет черного ферзя.
- `r` представляет черную ладью.
- `b` представляет черного слона.
- `n` представляет черного коня.
- `p` представляет черную пешку.
- Цифры (1-8) представляют пустые квадраты, причем число указывает количество последовательных пустых квадратов.

Например, `rnbqkbnr/pppppppp/8/8/8/8/ PPPPPPPP/RNBQKBNR` представляет начальную позицию в шахматной партии.

2. **Активный цвет (1 символ)**: Это поле указывает, очередь какого игрока делать ход. "w" обозначает ход белых, а "b" - ход черных.

3. **Доступность рокировки (1-4 символа)**: В этом поле указано, доступна ли рокировка для каждого игрока. Используются следующие символы:
- "K" для рокировки на королевском фланге белых.
- "Q" для рокировки на ферзевом фланге белых.
- `k` для рокировки на королевском фланге черных.
- `q` для рокировки на ферзевом фланге черных.
- `-`, если рокировка невозможна.

4. **Проходная целевая клетка (1-2 символа)**: Если пешка только что продвинулась на две клетки вперед от своей начальной позиции, это поле представляет клетку, которую пешка противника может захватить проходной. В противном случае оно отображается как `-`.

5. **Время полухода (1-2 символа)**: Это поле представляет количество полуходов (слоев) с момента последнего хода пешки или взятия. Оно используется для правила пятидесяти ходов.

6. **Номер полного хода (1-2 символа)**: Это поле представляет количество полных ходов (полных оборотов) в игре. Оно начинается с 1 и увеличивается после хода черных.

Вот пример строки FEN:
```
rnbqkb1r/ppp1pppp/5n2/3p4/3P4/8/PPP2PPP/RNBQKBNR w KQkq - 0 4
```
Это поле представляет собой конкретную позицию на доске, где настала очередь белых делать ход, у обеих сторон есть потенциал для замков на королевском и ферзевом флангах, нет проходной целевой клетки, время половины хода равно 0, а число полного хода равно 4.

Вы можете использовать нотацию FEN для записи определенных шахматных позиций и обмена ими, а также использовать их для различных целей, включая настройку пользовательских позиций для анализа или практики.
## Contributors
- [ZNackly](https://github.com/ZNackly)
## Mentors:
- Козлович Иван Алексеевич
