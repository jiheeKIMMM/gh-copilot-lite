# GitHub Copilot Workshop

이 워크샵에서는 [GitHub Codespaces](https://docs.github.com/ko/codespaces/overview)와 [GitHub Copilot](https://docs.github.com/ko/copilot/overview-of-github-copilot/about-github-copilot-business)을 이용해서 아래와 같은 실습을 진행합니다.

1. GitHub Copilot을 이용해 .NET 기반의 프론트엔드 앱 개발하기
1. GitHub Copilot을 이용해 .NET 기반의 백엔드 앱 개발하기
1. GitHub Copilot을 이용해 .NET 가빈의 백엔드 앱을 Java 기반의 Spring Boot 앱으로 이전하기
1. GitHub Copilot을 이용해 파워셸 및 Bash 셸 스크립트 작성하기

<!-- ![Overall Architecture](./docs/images/99-architecture.png) -->

## Prerequisites

이 워크샵을 진행하기 위해서는 아래와 같은 준비사항이 필요합니다.

- **개발 도구**
  - [GitHub Account](https://github.com/signup) 및 GitHub Copilot 구독 ([개인](https://docs.github.com/ko/copilot/overview-of-github-copilot/about-github-copilot-individual), [비지니스](https://docs.github.com/ko/copilot/overview-of-github-copilot/about-github-copilot-business) 또는 [엔터프라이즈](https://docs.github.com/ko/copilot/github-copilot-enterprise/overview/about-github-copilot-enterprise))
  - [Visual Studio 2022 17.10+](https://visualstudio.microsoft.com/?WT.mc_id=dotnet-121695-juyoo) 또는 [Visual Studio Code](https://code.visualstudio.com/?WT.mc_id=dotnet-121695-juyoo) + [C# Dev Kit 익스텐션](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit&WT.mc_id=dotnet-121695-juyoo)
  - [PowerShell 7.4+](https://learn.microsoft.com/ko-kr/powershell/scripting/install/installing-powershell?WT.mc_id=dotnet-121695-juyoo)
  - [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/ko-kr/windows/wsl/about?WT.mc_id=dotnet-121695-juyoo)
  - [GitHub CLI](https://cli.github.com/)
  - [Spring Boot CLI](https://docs.spring.io/spring-boot/installing.html#getting-started.installing.cli)

- **SDK**
  - [.NET 8 SDK](https://dotnet.microsoft.com/ko-kr/download/dotnet/8.0?WT.mc_id=dotnet-121695-juyoo)
  - [Microsoft OpenJDK 17+](https://learn.microsoft.com/ko-kr/java/openjdk/download?WT.mc_id=dotnet-121695-juyoo)
  - [Apache Maven](https://maven.apache.org/download.cgi)

## Getting Started

1. 이 리포지토리를 자신의 GitHub 계정으로 포크한 후 자신의 컴퓨터에 클론한 후 [이 문서](./docs/00-setup.md)부터 시작합니다.
2. 각 세션을 끝마치지 못했을 경우 이전 세션의 [세이브 포인트](./save-points)에서 시작할 수 있습니다.
3. 최종 완성본은 [`src`](./src) 디렉토리에서 확인할 수 있습니다.

## Sessions

| 세션                                            | 제목                                           |
|-------------------------------------------------|------------------------------------------------|
| [Session 00](./docs/00-setup.md)                | 개발 환경 설정                                 |
| [Session 01](./docs/01-blazor-frontend.md)      | Blazor 프론트엔드 웹 앱 개발                   |
| [Session 02](./docs/02-aspnet-core-backend.md)  | ASP.NET Core 백엔드 API 앱 개발                |
| [Session 03](./docs/03-spring-boot-backend.md)  | Java 기반 Spring Boot 앱 이전                  |
| [Session 04](./docs/04-shell-scripts.md)        | 셸 스크립트 작업                               |

## Resources

- [What is Blazor?](https://learn.microsoft.com/ko-kr/aspnet/core/blazor?WT.mc_id=dotnet-121695-juyoo)
- [Build your first Blazor app](https://dotnet.microsoft.com/ko-kr/apps/aspnet/web-apps/blazor?WT.mc_id=dotnet-121695-juyoo)
- [What is GitHub Copilot?](https://docs.github.com/ko/copilot)
- [Building an intelligent app with Blazor and Azure OpenAI](https://www.youtube.com/watch?v=TH12YSLLe9E&t=8464s)
