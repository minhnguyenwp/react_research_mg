<h1 align='center'>React Native Note</h1>
<br />
<h3>1. Install React Native Cli</h3>
<p>- See this link: https://facebook.github.io/react-native/docs/getting-started.html</p>
<p>--> Có thể chọn Windown hay Mac để cài đặt</p>
<p>--> Làm iOS và Android riêng biệt</p>
<hr />
<p>1.1 Làm iOS: thì phải có xCode & máy Mac dễ cài dễ test</p>
<p>1.2 Làm Android: thì phải có Python, Android Studio & máy android hay là Genymotion, cách cài <a href="https://hocthietkeweb.net.vn/huong-dan-cai-dat-may-ao-genymotion-de-test-ung-dung-android.html">xem link</a></p>
<p>Có thể xem các video hướng dẫn khởi tạo môi trường và test 
<a href="https://www.youtube.com/playlist?list=PLzrVYRai0riQsPYaBX-aNz8YCmtDsg17A">tại link này</a></p>
<h3>2. Style trong RN</h3>
<p>Có thể xem trong Giáo trình Khoa Phạm có nói rất dễ</p>
<p>* Nhớ xem các dùng FLEX để chia cột hàng vì APP nó không có dùng CSS như web.</p>
<p>--> Dùng với bộ UI component https://github.com/react-native-community/react-native-elements
<br /> hoac http://nativebase.io/ </p>
<p>--> LightBox https://github.com/oblador/react-native-lightbox </p>
<p>--> Slider https://github.com/leecade/react-native-swiper</p>
<p>--> Snap Carousel: slide từng item vào trọn màn hình : 
<br />---- https://www.npmjs.com/package/react-native-snap-carousel 
<br />---- https://github.com/machadogj/react-native-carousel-control
<br />---- https://github.com/jaysoo/react-native-parallax-scroll-view
</p>

<p>* Đủ thứ đồ chơi của RN: http://reactscript.com/</p>
<p>* Tổng hợp Component cho RN: https://github.com/booxood/fetch-react-native-components</p>

<h3>3. Viết 1 Component trong RN giống như làm với ReactJS</h3>
<p>Xem trong Khoa Phạm có nói rất dễ hiểu</p>
<h3>4. Router = Navigator trong RN</h3>
--> http://facebook.github.io/react-native/releases/0.41/docs/navigator.html#navigator
--> Cách viết xem Khoa Phạm hiểu cho nhanh xong roi coi cái nâng 
<p>--> REDUX-FLUX ROUTER trong RN https://github.com/aksonov/react-native-router-flux</p>
<p>--> Muốn protect page phải dùng global state để kiểm tra</p>
<p> Trước khi xem Link trên phải hiểu REDUX trong RN cài làm sao</p>
<h3>5. Redux </h3>
<p>Video hướng dẫn cài Redux cho REACT N https://www.youtube.com/playlist?list=PLk083BmAphjtGWyZUuo1BiCS_ZAgps6j5 </p>
<p>Source mẫu: https://github.com/aksonov/react-native-redux-router</p>
<h3>6. Cách viết App có Login & Register</h3>
https://www.youtube.com/playlist?list=PLkdLxQVsHYXxteWDEgOODl_UcRaa4x6t6
<h3>7. Use REdux-Observable</h3>
https://redux-observable.js.org/

- Bai viet: https://www.robinwieruch.de/redux-observable-rxjs/
VD: viết thực tế https://github.com/rwieruch/react-redux-soundcloud/blob/master/extension-observable/src/actions/auth.js 
<p>* Sài observable khi cần có chờ AJAX. </p>
<ul>
<li>Epic = Action </li>
<li> Dùng xen lẫn Redux va Obser</li>
</ul>
<hr />
<b style="color: 'red'">Sau khi đọc hiểu cài được môi trường</b>. Viết thử 1 APP như vd này. trước khi làm việc dự án chính.
https://viblo.asia/hieubm/posts/lA7GKnX4MKZQ
--> Viết detail cho 1 Book nữa. 
<p>* Có thể phải mua cái 
này để nghiên cứu: https://codecanyon.net/item/beostore-complete-react-native-template-for-ecommerce/17010642</p>
<p>Completed Source : https://github.com/7kfpun/FinanceReactNative </p>
<p>Completed Source : https://github.com/7kfpun/PhotosReactNativee </p>
<p>Nhiều module rất hay de học theo</p>


<h3>8. Add custom font to RN IOS</h3>
<p>iOS use xCODE: https://medium.com/@dabit3/adding-custom-fonts-to-react-native-b266b41bff7f#.oimfl0i7t</p>
<p>Android https://medium.com/@gattermeier/custom-fonts-in-react-native-for-android-b8a331a7d2a7#.hxsiggc30</p>

<h3>9. Cheatsheet style for RN</h3>
<p>https://github.com/vhpoet/react-native-styling-cheat-sheet</p>

<h3>10. Splash & Icon App</h3>
<p>ICON: https://blog.bam.tech/developper-news/how-to-generate-your-react-native-app-icons-in-a-single-command-line</p>
<p>SPLASH:
Later --> https://github.com/hypery2k/nativescript-media-generator
https://github.com/react-native-component/react-native-smart-splash-screen</p>
<p>https://github.com/bamlab/generator-rn-toolbox/blob/master/generators/assets/README.md</p>

<h3>11. Notification</h3>
<p>https://github.com/wix/react-native-notifications</p>

<h3>12. Local DB</h3>
<p>https://github.com/smartdemocracy/react-native-local-mongodb#speed</p>

<h3>13. List View</h3>
<p>- Refresh: https://www.youtube.com/watch?v=L8cZyXl37BU </p>
<p>- onEndReach in ListView</p>

<h3>14. Update Android_home</h3>
<p>- export ANDROID_HOME=/Users/{username-pc}/Library/Android/sdk     (/Users/minh/Library/Android/sdk)</p>
<p>- export ANDROID_HOME=/Users/minh/Library/Android/sdk</p>
<p>- update ADB: export PATH="/Users/minh/Library/Android/sdk/platform-tools":$PATH</p>
<p>- adb reverse tcp:8081 tcp:8081</p>

<h3>15. Net info - checking internet</h3>
<p>https://facebook.github.io/react-native/docs/netinfo.html</p>

<h3>16. DB </h3>
<p>- http://stackoverflow.com/questions/37342528/reactnative-best-approach-to-share-a-sqlite-instance-across-all-components-and</p>
<p>- REALM DB : https://realm.io/docs/javascript/latest/ </p>
<h3>17. Open Settings</h3>
<p>- https://github.com/rmrs/react-native-settings</p>

<h3>18. Upgrading RN</h3>
<p>https://facebook.github.io/react-native/docs/upgrading.html</p>

<h3>19. iOS After applying Splash - Shorter</h3>
<p>http://stackoverflow.com/questions/34027270/ios-launch-screen-in-react-native</p>
<p>My App does not use a launch image. Setting the "Launch Screen File" to my "main.storyboard" file fixed the issue for me.

This setting can be found under "Target->General->App Icons and Launch Images"

Use the following link for more information: http://oleb.net/blog/2014/08/replacing-launch-images-with-storyboards/
</p>

<h3>2018 REACT NATIVE</h3>
<p>* Good plugins: https://medium.com/rigor-solutions/awesome-components-for-your-next-reactive-native-project-6c4cded2e67a</p>
<p>2018. 2 - Cached Image: https://github.com/wcandillon/react-native-img-cache</p>
<p>2018. 3 (11.2018) - https://apiko.com/blog/10-react-native-open-source-projects-you-must-know/</p>
<p>iPhoneX - https://medium.com/react-native-training/react-native-iphonex-92ff511282af</p>
<p> IMAGE LOAD FAST: https://viblo.asia/p/thu-vien-load-anh-react-native-fast-image-YWOZr0JR5Q0</p>
<p>https://www.npmjs.com/package/react-native-snap-carousel</p>
<p>https://www.npmjs.com/package/react-native-image-slider-agb?activeTab=readme</p>
<p>https://github.com/phil-r/react-native-looped-carousel</p>
<p>*** Thư viện RN Comp: http://www.awesome-react-native.com/</p>
<h2>PUBLISH APP to STORE</h2>
<p>iOS: https://techmaster.vn/posts/8143/trien-khai-ung-dung-ios</p>
<p>After adding cert and provi, should restart MAC</p>
<p>https://play.google.com/apps/publish</p>
<p>UPGRADE: https://medium.com/@oleg2014/how-to-upgrade-project-to-react-native-0-57-rn-0-57-1a7e9fd8098</p>
