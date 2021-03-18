# Thế nào là một UI tốt?

![](https://webfuel.blob.core.windows.net/webfuel-filesystem/4fba2265-633b-bac3-efd1-08d3e0716398/blog/responsive-design-1.png)

Front end Application

> Thê nào là một UI tốt?

Trước khi đi vào các topic sâu hơn, trước tiền chúng ta cần thông nhất một số quan điểm chung về một UI tốt là như thế nào, trên cơ sở đó các topic tiếp theo sẽ bóc tách từng phần của vấn đề và trả lời câu hỏi **Làm sao để xây dựng được một UI tốt?**

**Một số quan điểm về UI tốt**

- Đẹp lung linh?
- Dễ dùng?
- Dễ maintain?
- Responsive ?
- Nhanh

**Vấn đề ở đây là gì**
- Mỗi người sẽ có một tiêu chuẩn khác nhau
- Không đồng nhất trong quan điểm
- Hướng tới những mục tiêu khác nhau

## Một góc nhìn

Chúng ta cần một góc nhìn chung để phân tích tiếp trong các topics sau, Chúng ta có thể tham khảo qua một góc nhìn. Đây hoàn toàn là quan điểm cá nhân mà chỉ mang tính chất đặt vấn đề và tham khảo.

> Một UI tốt có thể được đánh giá qua hai khía cạnh  **UX** và **DX**

- **UX** User Experience
- **DX** Developer Experience

Như mọi người đều biết **User Experience** là tối quan trọng, nhất là trong thời điểm hiện tại, người dùng có rất nhiều lựa chọn và đều là những lựa chọn tốt nếu trái nghiệm không tốt, người dùng sẽ có ngay lựa chọn khác. Có thể bạn nghĩ điều này không ảnh hưởng đến dev nhưng nhìn chung thì chất lượng sp đã không đáp ứng được thị trường thì việc bị đào thải là điều tất yếu.

Khái niệm **Developer Experience** có lẽ không phải thứ mà được nhiều người nhắc đến và quan tâm, chính xác hơn thì mình muốn nhắc đến development experience hay trải nghiệm phát triển một sản phẩm, và khi nhắc đến quá trình phát triển thì những người liên quan từ PM, Dev Team, PO,...

>  Tại sao **DX** lại quan trọng? 

Điều đầu tiên cần nhắc đến, nhất là với các công ty outsourcing thậm chí là product thì một trải nghiệm phát triển tốt, sẽ tiết kiệm được rất nhiều chi phí cho quá trình xây dựng phần mềm. Tạm thời chúng ta có thể hiểu DX là một trải nghiệm phát triển nhanh gọn, ít bug, dễ dang thay đổi nâng cấp mở rộng và dễ dng ứng biến với các yếu tố khác quan như đổi team, đổi sp, đổi khách hàng.

Mội **DX** tốt có nghĩa là team phát triển sẽ có quền kiểm soát tối đa với code base, hiểu rõ sản phẩm nên sẽ xây dựng sp chất lượng cao hơn. góp phần tăng UX.

> Hai yếu tố này bổ trợ cho nhau chứ không xung đột về mặt lợi ích, ít nhất là trong bối cảnh chúng ta đang xét đến.


## User Experience
![](https://oddslifenetstorage.blob.core.windows.net/casinobeats/2021/01/shutterstock_1745923076-e1610967018897.jpg)

> Thường khi nói đến Front end chúng ta có 2 terms là **UI** và **UX** sao ở đây ko nhắc đến **UI**?

Với vai trò là một Front end dev không nhiều trường hợp chúng ta có quền can thiệp quá nhiều vào UI, chúng ta có mockup, design, ý kiến khách hàng, thư viện. vậy tạm thời chúng ta sẽ dẹp chuyện xấu đẹp sang một bên. Không phải vấn đề này không quan trọng mà là xấu đẹp khó để đánh giá một cách khách quan và phụ thuộc nhiều vào xu hướng,  khách hàng cùng như tính chất của sản phẩm.

> Một Frot end developer nên quan tâm đến trải nghiệm người dùng hơn là sự xấu đẹp của UI?

Cũng không hẳn, một giao diện nhìn vào đã không muốn dùng còn không qua vòng gửi xe để xét đến UX.

Vấn đề chúng ta đang đặt ra là FE dev ngoài việc hoàn thành đúng UI (Design, mockup) thì một yếu tố vô cùng quan trọng đó là UX và câu hỏi luôn phải thường trực trong đầu đó là:

> Người dùng sẽ sử dụng UI của chúng ta như thế nào?

hiểu một cách đơn giản, UX sẽ xoay quanh 3 khía cạnh

![](https://www.realpointdesign.co.uk/wp-content/uploads/2016/05/uxchart.jpg)

Phần tiếp theo chúng ta sẽ thảo luận qua một số vấn đè ảnh hưởng trực tiếp đến UX mà chúng ta hay coi nhẹ hoặc bỏ qua.

### UI Component States 
![](https://lh5.googleusercontent.com/AMF_6BlBGPtCEcdppXRMF4TC6TM4SLriyaS48Q8Km9RwzLW6ZltYbuHOAwel6YBTJREmnvIhxVt-bbOOCNSQDUQUdEwAbok5frss4Bc8jEAuhKH_tfQycUTSub1G52yFDxjlj3QI)

Thường thì trong design hoặc mockup, thậm chí là trong task description chỉ provide cho chúng ta các UI design ở 1 trạng thái lý tưởng, nhưng như thế liệu đã đủ hay chưa?

Trên thực tế các UI components của chúng ta sẽ phải đối phó với nhiều trạng thái hơn thế ngoài trạng thái lý tưởng ra thì chúng ta phải hết sức để ý đến các trạng thái 

Đôi khi chúng ta cũng không cần thiết implement hết tất cả các state, nhưng phải luôn đảm bảo là sẽ cần implement bất kỳ lúc nào, bới vì nếu dự án sống đủ lâu sẽ đến lúc chúng ta sẽ cần 
implement nó. nên tại sao không chừa chỗ ra từ đầu.

Với một FE dev luôn phải quan niệm cho mình một UI component đến một ngày sẽ cần đủ các states. 

> hãy cảnh giác khi nghe câu  **Component này chỉ đơn gian hiện thị như thế này thôi là được.**,  tự chừa con đường cho mình :)

#### The Ideal State

![](https://miro.medium.com/max/1400/1*6hKDlrLKDtolPoaeWvg0Rg.png)

- nếu data y như design thì sẽ hiện thì như thế nào?
- nếu thay đổi kích thước màn hình thì có gì bị vỡ không?

Đây là trang thái cơ bản và rõ ràng nhất

#### The Blank State

![](https://miro.medium.com/max/1400/1*jvDAok82Rn-Jq15JtZMGWA.png)

-  nếu không có data component sẽ hiển thị gì?
- nếu user vào trang lần đầu thì sẽ thấy gì?
- nếu search ko ra kết quả thì hiện gì?
- nếu người dùng xoá hết data thì sẽ hiện gì?

#### The Loading State

![](https://miro.medium.com/max/1400/0*1k4ZRR565pe-J0ln.gif)

- nếu đang loading thì màn hình hiện gì?
- nếu mạng cực kỳ chậm thì sao?
- nếu trong lúc đang load user thực hiện action khác thì sao?

> Tips: Chrome network 3G Mode

#### The Partial State

![](https://miro.medium.com/max/1400/1*Qs66iwT4TPRBR7MWi_805g.png)


#### The Imperfect State

 ![](https://miro.medium.com/max/1400/1*x8EBEoRAHSVG3VTfrhs8jg.png)


#### The Interactive State

![](https://miro.medium.com/max/1400/1*O6a76lYE3XvauSBvQJA6tQ.png)

#### The Error State

![](https://miro.medium.com/max/1400/1*arupaxyBBZxnnyULBd6Rzw.png)

#### The Success States

![](https://miro.medium.com/max/4800/1*mQaM-gAFe9WzolS_vQoe4A.png)

### Responsive/Adaptive

![](https://kinsta.com/wp-content/uploads/2020/08/responsive-adaptive-design.png)

### Consistency

#### Visual Consistency

1. Typography
![](https://miro.medium.com/max/2400/1*s6OqC7mSHfIaHLQHvlYUGw.png)

2. UI Elements
- Spatial 
- Images 
- Size 

3. Color

#### Behavior Consistency

![](https://www.areteworks.com/wp-content/uploads/2018/10/popup-300x222.png)

[https://ux.stackexchange.com/a/1077](https://ux.stackexchange.com/a/1077)

### Provide Feedback

![](https://miro.medium.com/max/1000/1*U1xCz37uah8qJQgDh6X56g.jpeg)

Mỗi hành động mang tính tương tác người dùng đề mong đợi mội phản hồi đề họ biết họ được làm gì và không được làm gì tiếp theo.

 khi hover vào 1 element clickable: 

```css
a:hover {
	cursor: pointer;
}
```

![](https://bashooka.com/wp-content/uploads/2019/07/css-js-file-upload-example-12.jpg)


![](https://i.ytimg.com/vi/HnTWyfuN_Do/maxresdefault.jpg)

### Performance

![](https://treo.sh/assets/files/metrics-2x.e4e87e4.jpeg)

[https://web.dev/user-centric-performance-metrics/](https://web.dev/user-centric-performance-metrics/)

### Tools 
- webpack-bundle-analyzer

![](https://cloud.githubusercontent.com/assets/302213/20628702/93f72404-b338-11e6-92d4-9a365550a701.gif)

- Goodle PageSpeed Insights
![](https://developers.google.com/speed/pagespeed/images/psi.png)

- Chrome Dev tols
![](https://lh3.googleusercontent.com/SQAN4lUbjX313cKU_yFEt1IcCjXf7yQNq5ZdC8hBfsi9AT-Yz4tE3nyJkcovKDTpHHSPWWPgYo62OzQQ4ogULnEckA=w640-h400-e365-rj-sc0x00ffffff)
![](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/imgs/zoomed.png)

- Can I use
![](https://hacks.mozilla.org/files/2019/09/Screenshot_2019-09-09-Can-I-use-Support-tables-for-HTML5-CSS3-etc.png)


## Developer Experience
![](https://miro.medium.com/max/680/1*IRGHmiGsa16stedQvIaZfw.gif)

![](https://hackernoon.com/hn-images/0*pmgC6tviGfb1MSOc.jpg)

Như đã gới thiệu trước đó **DX** đóng vai trò rất quan trọng trong thành công của dự án pm cũng như sự thành công của một sp pm trên trị trường.

Có nhiều yếu tố ảnh hưởng đến **DX** dưới đây chúng ta sẽ đi qua một số.

### Clear structure

Một vài kiểu structure
- Flat structure
- Modulize Structure
- View state Structure

![](https://michalzalecki.com/posts/elegant-frontend-architecture-domain@2x.jpg)
![](https://miro.medium.com/max/1400/1*T_Q66EkNEhca6TyrvY1xBQ.gif)

Cấu trúc thế nào là tốt.

- Tách biệt
- tái sử dụng
- rõ ràng
- dễ tean work
- dễ maintain

Các Rules
- **open for extension, closed for modification**
- **Single source of truth**
- **One Way Data Flow**
- **Separating business and UI logic**
- **Lifting State Up**

![Lifting State Up](https://images.viblo.asia/f1be4df7-31a3-4d6f-959e-e7540bc81167.png)


### Code spliting
![](https://cdn.filestackcontent.com/tLOD9fSJT8qoyihLuZU0)

### Error Handling
![](https://i.stack.imgur.com/fRuZJ.png)


Các loại lỗi
- Server errors. These are errors returned by the API and include fatal errors, request errors and logic errors.
- Network errors. These errors occur when the API is not accessible or when a chunk of code cannot be loaded when code splitting is used.
- Routing errors. These errors indicate that the URL in the browser is invalid and cannot be mapped to a valid route.
- Authorization errors. These errors occur when the user is not authenticated or doesn’t have access to the given page or data.
- Form validation errors. These errors are displayed when some value entered by the user is invalid.
- Fatal errors. Other kinds of errors that are usually the result of a programmer’s error in the application code fall into this category.

Cần quan tâm
- Error pages
- Error Interceptors
- Error boundary
- Error Alert

Các công cụ:
- Error boudary
- try catch
- Sentry crashlytics
- Firebase crashlytics 

### Workflow
![](https://topdev.vn/blog/wp-content/uploads/2018/05/ci-cd-intro.png)

- CI/CD
- Docker
- Webpack
### Teamwoking
![](https://cdn5.vectorstock.com/i/1000x1000/06/09/a-young-team-working-together-to-solve-a-problem-vector-21750609.jpg)

### Reuseable 

![](https://miro.medium.com/max/793/1*SlAPqCmjtwvRsn0Kszi7oA.png)

![](https://miro.medium.com/max/1018/1*0lvyAHxRcP7HTDaToUsjbg.png)

Case study `Bit.dev`
[](https://bit.dev/)

- Micro front end
- Yarn/Npm workspace
- create react libraly

### Testing 
![](https://image.slidesharecdn.com/jesttalk-enterjs-180622081155/95/jest-frontend-testing-leicht-gemacht-enterjs2018-7-638.jpg?cb=1529655223)

chúng ta chia FE testing ra các level
- **End to End**: A helper robot that behaves like a user to click around the app and verify that it functions correctly. Sometimes called "functional testing" or e2e.
- **Integration**: Verify that several units work together in harmony.
- **Unit**: Verify that individual, isolated parts work as expected.
- **Static**: Catch typos and type errors as you write the code.

Các công cụ:

- Jest
- Mocha 
- Chai

- Enzym 

- cypress.
- Selenium


## Good Front end developer?

- Hãy quan tâm đến ``UX`` và ``DX``

## References:
- [35 quick tips to improve web performance](https://uxdesign.cc/35-quick-tips-about-web-performance-114b8fab0d6)
- [Characteristics of a Good Web application](https://www.zensar.com/blogs/2016/06/characteristics-of-a-good-web-application/)
- [12 Attributes of a Good Web Application Architecture](https://www.codeproject.com/Articles/841318/Attributes-of-a-good-web-application-architecture)
- [10 Rules of Good UI Design to Follow On Every Web Design Project](https://www.elegantthemes.com/blog/resources/10-rules-of-good-ui-design-to-follow-on-every-web-design-project)
- [What makes a good user interface?
](http://uw714doc.sco.com/en/SDK_vtcl/vtclgN.style_goodui.html#:~:text=A%20clear%20interface%20helps%20prevent,and%20consistent%20with%20one%20another.)
- [Designing for different states in the UI](https://uxdesign.cc/designing-for-different-ui-states-87d60130f85f)
- [The Nine States of Design](https://medium.com/swlh/the-nine-states-of-design-5bfe9b3d6d85)
