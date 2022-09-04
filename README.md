# maui-learn

## 작업 완료 현황

- [x] MAUI를 사용하여 플랫폼 간 앱 만들기
- [x] XAML을 사용하여 MAUI 앱에서 UI 만들기
- [ ] MAUI XAML 페이지에서 레이아웃 사용자 지정
- [ ] 공유 리소스를 사용하여 일관된 MAUI XAML 페이지 디자인
- [ ] 탭 및 플라이아웃 탐색을 사용하여 다중 페이지 MAUI 앱 만들기
- [ ] MAUI 앱에서 REST 웹 서비스 사용
- [ ] MAUI 앱에서 SQLite를 사용하여 로컬 데이터 저장
- [ ] Blazor Hybrid 및 MAUI를 사용하여 모바일 및 데스크톱 앱 빌드

## 학습 경로

- [MAUI를 사용하여 모바일 및 데스크톱 앱 빌드](https://docs.microsoft.com/ko-kr/learn/paths/build-apps-with-dotnet-maui)

	MAUI를 통해 C# 및 Visual Studio를 사용하여 모바일 디바이스 및 데스크톱에서 실행되는 앱을 빌드하는 방법을 알아봅니다. MAUI를 사용하여 앱을 빌드하는 기본 사항과 로컬 데이터 스토리지 및 REST 기반 웹 서비스 호출과 같은 고급 항목을 알아봅니다.

## 학습 모듈

---

1. [MAUI를 사용하여 플랫폼 간 앱 만들기](https://docs.microsoft.com/ko-kr/learn/modules/build-mobile-and-desktop-apps)

	MAUI에서 Visual Studio를 사용하여 플랫폼 간 앱을 만드는 방법을 알아봅니다.

### 요약
.NET MAUI는 Windows, Android, macOS 및 iOS 장치에서 실행할 수 있는 플랫폼 간 앱을 만드는 방법을 제공합니다.

이 모듈에서는 다음을 수행합니다.
- MAUI의 기본 아키텍처를 배웠습니다.
- MAUI 앱 생성
- MAUI에서 지원하는 플랫폼에 대한 공유 UI 정의
- Visual Studio에서 .NET MAUI 앱 배포
- MAUI를 사용하여 플랫폼 API에 액세스

Windows 및 Android에서 실행되는 .NET MAUI 앱을 빌드했습니다. 또한 .NET MAUI API를 사용하여 두 플랫폼 모두에서 전화 걸기 장치에 액세스했습니다. 이 앱은 소개에 정의된 요구 사항에 대한 개념 증명 역할을 합니다. 특히 다음과 같은 앱을 만들기 시작했습니다.

- Windows, Android 및 기타 지원되는 장치에서 실행됩니다.
- 개발 시간을 최소화합니다.
- 전화 걸기에 액세스할 수 있습니다.
---

2. [XAML을 사용하여 MAUI 앱에서 UI 만들기](https://docs.microsoft.com/ko-kr/learn/modules/create-user-interface-xaml)

	XAML을 사용하여 MAUI 앱용 UI를 디자인하는 방법 알아보기

### 요약
코딩된 UI는 레이아웃과 동작을 관리하기 어렵게 만듭니다. 이 접근 방식에는 레이아웃과 행동 논리가 포함되는 경우가 많으며 결과적으로 둘 사이가 긴밀하게 연결됩니다. UI 디자인을 변경하면 나머지 코드베이스에 연쇄 효과가 발생할 수 있습니다. UI와 동작이 명확하게 분리되지 않은 코드베이스를 유지 관리하는 것은 어려울 수 있습니다.

MAUI를 사용하면 XAML을 사용하여 UI를 정의할 수 있습니다. 이 분리를 통해 C# 코드 파일의 동작 논리에 집중할 수 있습니다. 이제 UI 디자이너는 UI에 집중할 수 있고 프로그래머는 코드에 집중할 수 있습니다.

MAUI XAML을 사용하면 태그 OnPlatform확장을 사용하여 각 플랫폼에 대한 UI를 사용자 지정할 수 있습니다. 이 접근 방식을 사용하면 OS별 UI 기능을 사용할 수 있지만 여전히 모든 플랫폼에서 보기 좋은 앱을 디자인할 수 있습니다.

이 모듈에서는 XAML을 사용하여 플랫폼 간 앱용 UI를 디자인하는 데 가장 효과적인 방법을 살펴보았습니다. 구체적으로 다음을 배웠습니다.

- C#에서 MAUI 앱의 UI를 정의하는 것보다 XAML을 사용할 때의 이점
- 페이지 및 컨트롤을 만들고 XAML을 사용하여 해당 속성을 설정하는 방법
- UI 이벤트를 처리하고 XAML에 연결하는 방법
- XAML 태그 확장을 만들고 사용하는 방법
- XAML 태그에서 플랫폼별 값을 설정하는 방법
---

3. [MAUI XAML 페이지에서 레이아웃 사용자 지정](https://docs.microsoft.com/ko-kr/learn/modules/customize-xaml-pages-layout)

	StackLayout 및 Grid를 사용하여 여러 디바이스에서 일관적인 사용자 인터페이스를 만듭니다.

	이 모듈에서는 다음을 수행합니다.
	- 앱에서 사용자 인터페이스 요소를 정렬하고 크기 조정
	- StackLayout을 사용하여 세로 또는 가로 목록으로 보기 표시
	- 그리드를 사용하여 행과 열에 보기 표시
---

4. [공유 리소스를 사용하여 일관된 MAUI XAML 페이지 디자인](https://docs.microsoft.com/ko-kr/learn/modules/use-shared-resources)

	MAUI XAML에서 공유 리소스 및 스타일을 사용하는 방법 알아보기

	이 모듈을 마치면 다음을 수행할 수 있습니다.
	- MAUI XAML 사용자 인터페이스에서 정적 리소스 생성 및 사용
	- 동적 리소스 생성 및 사용
	- 스타일을 사용하여 일관된 사용자 인터페이스 만들기
	- 애플리케이션 전체 리소스 생성 및 사용
---

5. [탭 및 플라이아웃 탐색을 사용하여 다중 페이지 MAUI 앱 만들기](https://docs.microsoft.com/ko-kr/learn/modules/create-multi-page-apps)

	MAUI 셸을 사용하여 탭 및 플라이아웃 탐색으로 다중 페이지 애플리케이션을 만듭니다.

	이 모듈을 마치면 다음을 수행할 수 있습니다.
	- MAUI 셸로 탭 탐색 구현
	- 탭 페이지 내 페이지 간 탐색
	- MAUI 셸을 사용하여 플라이아웃 탐색 구현
---

6. [MAUI 앱에서 REST 웹 서비스 사용](https://docs.microsoft.com/ko-kr/learn/modules/consume-rest-services-maui)

	HttpClient를 사용하여 REST 웹 서비스를 사용하고 기본 CRUD 작업을 수행합니다. 디바이스가 인터넷에 연결된 시기를 검색하여 좋은 사용자 환경을 제공하고 네이티브 네트워킹 스택을 이용하여 최고의 성능을 얻습니다.

	이 모듈에서는 다음을 수행합니다.
	- 장치가 인터넷에 연결되어 있는지 감지
	- HttpClient를 사용하여 REST 웹 서비스 사용
	- HttpClient를 사용하는 동안 기본 네트워킹 스택 활용
---

7. [MAUI 앱에서 SQLite를 사용하여 로컬 데이터 저장](https://docs.microsoft.com/ko-kr/learn/modules/store-local-data)

	MAUI 앱을 사용하여 SQLite에 보관된 데이터를 저장하고 액세스하는 방법 알아보기

	이 모듈에서는 다음을 수행합니다.
	- MAUI 애플리케이션에 사용할 수 있는 다양한 데이터 스토리지 옵션 비교
	- SQLite 데이터베이스에 관계형 데이터 저장
	- UI가 응답성을 유지하도록 데이터베이스와 비동기식으로 상호 작용합니다.
---

8. [Blazor Hybrid 및 MAUI를 사용하여 모바일 및 데스크톱 앱 빌드](https://docs.microsoft.com/en-us/learn/modules/build-blazor-hybrid)

	개발 환경을 설정하고 Blazor, MAUI 및 C#을 사용하여 첫 번째 플랫폼 간 하이브리드 앱을 빌드하는 방법을 알아보세요.

	이 모듈에서는 다음을 수행합니다.
	- Visual Studio를 사용하여 Blazor 하이브리드 개발을 위한 로컬 환경 구성
	- Blazor Hybrid 앱의 기본 아키텍처 알아보기
	- MAUI로 구동되는 새로운 Blazor Hybrid 프로젝트 생성
	- Blazor Hybrid 앱에 클라이언트 쪽 논리 추가
	- MAUI를 사용하여 모바일 및 데스크톱용 플랫폼 기능에 액세스
	- Visual Studio에서 Blazor 하이브리드 앱 배포