-   _positon_: có 5 giá trị chính: static, relative, absolute, sticky, fixed;
-   _relative_: khi sử dụng gia trị này thì phải lưu ý xem phẩn tử con của nó có sử dụng position là `absolute` hay không ?;
-   _absolute_: can use with position in css.
-   Thẻ _a_: thì nên dùng thêm `rel`: _noopener_ && _noreference_;

**box-sizing**:

-   _content-box_: Độ rộng của một khối bằng width + padding + border;
-   _border-box_: Độ rộng của khối sẽ bao gồm margin và padding;

**display: flex;**

-   _flex-direction: row-column_; --> dùng để xác định hướng của item(+reverse để có thể đảo chiều item);
-   _align-items: stretch_; --> là thuộc tính mặc định của _align-items_, nếu flex-direction là row thì nó sẽ làm item có chiều cao bằng nhau, còn nếu flex-direction là column thì sẽ làm các item có chiều rộng bằng nhau;
-   _align-item: flex-start || flex-end_: thuộc tính điều chỉnh vị trí của item theo trục dọc ở vị trí start || end;

**Position**

-   _position_: có 5 giá trị: static, relative, absolute, sticky, fixed;
-   _relative_: Khi sử dụng giá trị này thì phải lưu ý xem phần tử con có sử dụng `position: absolute` không?
-   _absolute_: Khi sử dụng gí trị này thì phải xem phần tử chứa nó có sử dụng `position` là `absolute` hay `relative` hay không?

_Transform_ - `translate`(translateX, translateY), `skew`(skewX, skewY), `rotate`(rotateX, rotateY, rotateZ), `scale`(scaleX, scaleY)

**Grid**

-   _display:grid_: -> `justify content: start end center baseline strech`, `align content: start end center space-around space-between`
-   _trackline_: start -> 1 and end -> -1;
-   _grid-template-columns_: value value value | Ex: grid-template-column: 270px 270px 270px;

-   _css slector child_: `nth-child(number,...)` -> chọn những phần tử cùng cấp.

-   _list-style-type_: thuộc tính này dùng cho thẻ ul(`disc`) và ol(`decimal`)
-   _list-style-position_: outside hoặc indise

-   _inputmode_: `search`, `decimal`, `tel`, `number`, `email`, `url`
-   _sass_: sẽ có 2 đuôi mở rộng là `.scss` hoặc `.sass`(không dùng dấu `{}`) --> `sass path-of-sass-file path-of-css-file --watch`
