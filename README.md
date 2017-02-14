**React Quiz**
-- 8 lưu ý khi làm việc với React.
https://blog.duyetdev.com/2016/06/8-dieu-reactjs-beginner-nen-biet.html

1. JSX làm gì trong REACTJS
2. Babel là gì? 

3. Props là gì? giong nhu property ngoai truyen vao trong comp. khong thay doi ben trong. 
4. State là gì? Trang thai gia tri ben trong 1 Comp, thay doi lien tuc ben trong. 
5. Props VS State ? props cha truyen xuong con dc, con truyen ra ngoai.
----------------------- props VS state ------------------------
Features	                                    props	  state
Can get initial value from parent Component?	 Yes	   Yes
Can be changed by parent Component?	             Yes	    No
Can set default values inside Component?*	     Yes	   Yes
Can change inside Component?	                  No	   Yes
Can set initial value for child Components?	     Yes	   Yes
Can change in child Components?	                 Yes	    No

6. Làm sao truyền giá trị từ Child Comp lên Parent Comp?
7. Ref là gì trong Comp? Truyền JSON dc không?
8. Làm Form có validation trong reactJS làm sao?
9. Làm 1 slider bằng jQuery làm như thế nào?
10. Làm sao setup 2-way bindding cho react?
11. Lấy data từ API có mấy cách (AJAX)? 
Xem https://hashnode.com/post/5-best-libraries-for-making-ajax-calls-in-react-cis8x5f7k0jl7th53z68s41k1 
* use Request or fecth
. Root Component
. Container Components
. Redux Async Actions (FLUX)
. Relay
12. FLUX là gì tại sao phải dùng FLUX?
13. React có nhiều trang nhiều URL thì cần làm gì?
https://www.kirupa.com/react/creating_single_page_app_react_using_react_router.html
14. Làm sao viết Conditional Rendering 
15. Kể tên các events thường dùng trong reactJS
https://facebook.github.io/react/docs/events.html
16. Mixin làm vai trò gì trong react.
17. Làm sao override kế thừa 1 class.
18. Truyền gia tri qua cac comp: 
18.1 http://stackoverflow.com/questions/40377118/reactjs-parent-component-communicate-with-child-of-child-component
18.2 http://stackoverflow.com/documentation/reactjs/6567/communication-between-components#t=201702060643011229497

19. react-starter-kit : https://github.com/kriasoft/react-starter-kit
19.1 Add sass 
https://github.com/kriasoft/react-starter-kit/blob/master/docs/recipes/how-to-use-sass.md

20. https://github.com/start-react/sb-admin-react

21. Reference
https://www.icicletech.com/blog/16-opensource-reactjs-projects-to-learn-from

Study : https://github.com/andrewngu/sound-redux 
ReactJS + Redux + backend.

22 * Redux Study.
https://github.com/erikras/react-redux-universal-hot-example
https://medium.com/@rajaraodv/a-guide-for-building-a-react-redux-crud-app-7fe0b8943d0f#.koqrvuca8

Study how does redux work .
- DEMO: https://protected-escarpment-79486.herokuapp.com/signup
- https://github.com/rajaraodv/react-redux-blog/tree/master/public/src/reducers

TOP starter: http://andrewhfarmer.com/starter-project/

* Understand How Redux works: 
- Giúp quản lý từng Page có các actions và states gì? đồng thời lưu thông tin hành động đó cùng state từng trường hợp.
VD: trang login có 
- Actions: Submit - Check Valid - Cancle - Success
- State là Success - InValid - Begin (blank)

1. Elements:
- Actions: Là các hành động tương tác làm thay đổi State của Comp đó. submit hay là data dc load ve thành công.
--> Nơi đăng ký các hành động, kể cả request API và trả ra payload.
Payload là bất kỳ kết quả nào để thay doi giá trị state của page đó. 
vd: https://github.com/rajaraodv/react-redux-blog/blob/master/public/src/actions/posts.js
Trong file trên có 2 phần. 
-.1 dispatch action : tạo action với các constant hệ thống, dẫn đường cho action.
-.2 action creator : xử lý action và kết quả trả về paypload.

- Reducers: Nơi đăng ký mỗi hành động sẽ tương ứng với các state như nào. 
--> Đồng thời file này cũng giúp theo dõi và chuyển đổi state theo các action. 
Vd: https://github.com/rajaraodv/react-redux-blog/blob/master/public/src/reducers/reducer_posts.js
-.1 Gọi actions
-.2 đăng ký state khởi tạo. 
-.3 kết nối action và state. 
-.4 Sau khi tạo dc các reducer, cần tạo 1 file gọi các reducer lớp Global trước https://github.com/rajaraodv/react-redux-blog/blob/master/public/src/reducers/index.js#L3
các reducer dùng giới hạn trong 1 page thì sẽ gọi sau khi cần. 
- Store: Khai báo de lưu trữ và Middleware de theo dõi ghi log action va state.
https://github.com/rajaraodv/react-redux-blog/blob/master/public/src/store/configureStore.dev.js
trong này gọi cac reducer vào để theo dõi. file trên setup theo kiểu hot module.
- Middleware: Là phần thứ 3 giúp hỗ trợ theo dõi trong redux.
--> Có thể override middleware, phần lớn là để promise chuyển tiếp giữa các action. 

2. Workflow:
2.1- Async Actions: là các xử lý trong action, rõ nhất là lấy data từ api. 
vd: https://github.com/rajaraodv/react-redux-blog/blob/master/public/src/actions/posts.js

2.2- Async Workflow: Đó là việc tạo reducer kết nối action với các state. và khai báo store để chờ theo dõi.

2.3- Redux Router: 
Đây là việc khai báo kết nối giữa việc thay đổi router (đi qua lại giữa các trang) và lưu trữ history 
-.1. npm install --save react-router
-.2. xem file https://github.com/rajaraodv/react-redux-blog/blob/master/public/src/index.js 

23. Use parameter in URL 
--> https://github.com/reactjs/react-router-tutorial/tree/master/lessons/06-params

24. Ahth in React by Router. 
https://github.com/erikras/react-redux-universal-hot-example/blob/master/src/routes.js
