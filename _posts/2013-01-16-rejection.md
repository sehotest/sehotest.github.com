---
layout: entry
title: app store rejection
author: seho lee
author-email: seholee@seho.com 
description: rejection reasons
---

별 것도 아닌 것 같은데 App Store에서 rejection 되었습니다.
무료 demo 버전을 올렸는데, demo라는 개념을 받아 드리지 않네요.
Free 또는 Lite 이란 단어는 괜찮다고 하네요.

"Demo" 라는 단어는 사용금지!!!

+++
iPhone AppStore Reject 사례
2010/01/26 11:58 from Objective-C, iPhone SDK

1. default.png 이미지 없는 경우 가이드 라인 위반.

2. 공개되지 않은, 문서화되어 있지 않은 API나 기본 Framework의 객체 속성을 건드리는 경우
예) UIImagePickerViewController를 상속받아 카메라 촬영화면을 커스터마이징

3. 테이블 뷰에 리스트를 표시하고 항목을 하나 고르면 세부항목으로 들어가는, master-detail 구조에서 리스트 내용을 Edit버튼을 통해 추가 삭제가 가능한 경우에 리스트 목록이 없는데도 Edit 버튼이 있어서 가이드 라인 위반. (리스트 내용이 없으면 Edit 버튼이 보이지 않아야 함)

	4. 네트워크 연결이 실패했을 때 사용자 인터렉션이 불가능한 경우 가이드 라인 위반.

	5. 유료버전이 있는 상태에 무료버전 배포시에 무료에 유료기능을 완전히 삭제하는 것이 아닌 "무료라서 안됨~ㅋ" 이라고 메세지를 보여주는 경우. 각 버전의 완결성이 있어야 함.


	6. 저작권 관련해서 애플 상품 이미지를 사용하는 경우.

	7. 전화번호를 삽입하여 보여주는 경우.

	8. App Name 과 Product Name 이 다른 경우.

	9. WebView 사용시에 로딩 이미지 미적용 가이드 라인 위반.

	10. [+] 아이콘 사용시 주소록 [+] 과 디자인이 비슷하다는 가이드라인 위반.

	11. App 내에 다른 App 홍보를 위한 이미지에 가격이 나와 있는 경우 위반. ($1.99 같은 경우 달러화를 쓰지 않는 국가에서 혼돈)

	12. WebView 를 사용하는 경우 사용등급(Rating) 을 최고 등급으로 올려야 함. WebView 를 사용함으로써 음란 사이트에 접속할 수 있다는 이유.

	13. 아이콘 사이즈 별로 동일한 이미지 등록하지 않는 경우. (약간만 달라도 Reject)

	14.  App 내에 정보가 다른 곳으로 전송될 때는 반드시 사용자가 알수 있는 표시를 하지 않는 경우.

	15. 업데이트 버전일 경우 버전 명시가 정확하게 되지 않은 경우. (버전 정보가 없어도 상관 없으나 있는 경우에만)


	출처: osxdev.org 와 mcbugi 카페
	Android 보다 Apple 이 많이 까다롭다고 하구요.(퀄리티 차이가 나는 부분일지도)
	대부분  HIG 위반 사례이네요. 꼭 읽어봐야 할 것 같습니다..


+++++++

<span style="color: rgb(67, 65, 66); line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px;" class="Apple-style-span"><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><strong style="border-width: 0px; margin: 0px; padding: 0px; line-height: normal; font-size: 14px; background-color: transparent;">놓치기 쉬운 Appstore Reject 사유 20 가지</strong></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">Apple에서 배포한 Review Guide와 실제 Reject 된 사유 중 놓치기 쉬운 주요 사항을 정리해보았습니다. 본 글은 기능에 대한 Reject 사유 보다는 개발자들이 놓칠 수 있는 내용을 중심으로 구성하였으며 상세 Reject 에 대한 내용은 Apple에서 배포한Review Guide 를 참고하시기 바랍니다.</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">1. Descrip-tion등에 애플 정책에 대한 언급 시 reject</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">2. 앱 이름에 영문으로 아이폰, 아이패드 등을 넣을 경우 iPod, iPad, iPhone 로 애플의 표기법을 따라야 함</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">3. 스크린상에 아이폰, 아이팟 등의 이미지 노출 시 reject (애플 상품, 상표 이미지뿐 아니라 기타 저작권/상표권 위반, 표절 이미지도 금함)</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">4. Descrip-tion, 아이콘 등의 이미지에 가격 정보 노출 시 reject</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">5. "beta", "demo", "trial", or "test" 단어는 reject 사유이며, “Lite” 나 “Free”로 표기할 것을 권장</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">6. 로딩 이미지 없이 웹 페이지를 불러 올 시 reject</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">7. 57*57, 72*72, 512*512 아이콘 이미지는 모두 동일한 이미지를 사용해야 함</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">8. 탭바 아이콘에 별 이미지를 사용할 경우 “Favorite” 메뉴로 사용할 것을 권장</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">9. 경품 이벤트의 경우 애플과 무관함을 명시하지 않을 경우 reject</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">10. app name과 product name 이 다를 경우 reject</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">11. 기부 기능을 가진 app 은 무료로 배포되어야 하며, 유료 판매 후 수익금을 기부하는 형태나 de이 있을 경우 reject</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">12. 성적으로 자극될 수 있는 내용 및 이미지 등이 있을 경우 reject</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">13. 어플명에 스티브잡스라는 단어 및 관련 이미지 사용 시 reject</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">14. 욕설, 비속어 등이 사용되면 reject (사전 app 도 불가함)</span><br style="margin: 0px; padding: 0px;" /><span style="font-size: 10pt;">&#65279;</span></p><p style="border-width: 0px; margin: 0px 0px 24px; padding: 0px; line-height: 23px; font-family: 굴림, Gulim, 돋움, Dotum, AppleGothic, sans-serif; font-size: 14px; background-color: transparent;"><span style="font-size: 10pt;">15. 전화번호를 자동으로 받아오는 경우</span></p><div><span style="font-size: 10pt;">출처 : olleh</span></div></span><p><span style="font-size: 10pt;">&nbsp;</span></p><p><span style="font-size: 10pt;">



</span>&nbsp;</p><p><span style="font-size: 10pt;">&#65279;16. 메타데이타에&nbsp;iOS기반 플랫폼 화면이 아닌 것이 있는 경우</span>&nbsp;</p><p><span style="font-size: 10pt;"></span>&nbsp;</p>
</div>

