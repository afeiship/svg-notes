# circle


## 圆环
```html
 <svg class="c-c-c">
        <circle cx="48" cy="48" r="40" stroke="#eee" stroke-width="15" fill="none" stroke-dashoffset="<%=80*Math.PI%>px"/>
        <circle cx="48" cy="48" r="40" stroke="<%=color%>"
        stroke-width="15" fill="none" stroke-dasharray="<%=score*8*Math.PI%>px, <%=80*Math.PI%>px" class="blue-circle"/>
                                                        <!-- 此处前面值为圆环占的值，后面值为圆环总长度 -->
        <text x="40" y="56" fill="<%=color%>" font-size="25">25%</text>
 </svg>
```
