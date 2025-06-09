# Currency Exchange
<br />

## 1. 소개
> 실시간 환율 정보를 시각적으로 제공하는 WPF 기반 데스크톱 애플리케이션입니다. <br />
> 다크 테마 UI와 카드 스타일의 통화 목록을 통해 사용자 친화적인 경험을 제공합니다.

<br />

### 작업기간
2025/06, 1주
<br /><br />

### 인력구성
1인
<br /><br /><br />

## 2. 기술스택

<img src ="https://img.shields.io/badge/C_sharp-003545.svg?&style=for-the-badge&logo=Csharp&logoColor=brown"/>  <br /><br /> <br />

## 3. 기능 
- 실시간 환율 데이터 조회
- 카드 스타일의 통화 정보 표시
- 상승/하락/변동 없음 아이콘 및 색상 표시
- 다크 테마 기반의 현대적인 UI
- MVVM 아키텍처 기반의 구조
<br /><br />

## 4. 📂 Project Structure (폴더 구조)
```
Currency/
├── Views/                      # XAML 뷰와 사용자 인터페이스
│   ├── MainWindow.xaml/.cs        # 메인 애플리케이션 창 UI
│
├── ViewModels/                # MVVM 패턴의 ViewModel들
│   └── MainViewModel.cs       # 메인 ViewModel (비즈니스 로직 포함)
│
├── Models/                    # 데이터 모델 및 엔터티 정의
│   ├── Currency.cs            # 개별 통화 모델 정의
│   └── ExchangeResponse.cs    # 환율 API 응답 모델
│
├── Services/                  # 비즈니스 로직 및 외부 서비스 연동
│   └── CurrencyApiService.cs  # 환율 API와의 통신을 담당하는 서비스
│
├── Helpers/                   # 유틸리티 클래스 및 헬퍼 함수
│   ├── ObservableObject.cs    # INotifyPropertyChanged 구현 기반 클래스
│   └── RelayCommand.cs        # MVVM용 ICommand 구현 클래스
│
├── Resources/                 # 애플리케이션 리소스 및 스타일
│   └── Styles.xaml            # 전역 스타일 및 테마 정의
│
├── App.xaml                   # 애플리케이션 진입점 및 전역 리소스 정의
├── App.xaml.cs                # 애플리케이션 초기화 로직
├── AssemblyInfo.cs           
├── currency.csproj           
└── currency.sln              

```
<br /><br />



