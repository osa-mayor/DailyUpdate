# 🟠 Hacker News Daily Top 10 (2026-04-15)

## 1. [Someone bought 30 WordPress plugins and planted a backdoor in all of them](https://anchor.host/someone-bought-30-wordpress-plugins-and-planted-a-backdoor-in-all-of-them/)
**Score**: 1123 | **Comments**: 314 | **Rank Score**: 787.947
**작성자**: speckx | **게시 시각(KST)**: 2026-04-14T02:54:39+09:00
**Hacker News 토론**: https://news.ycombinator.com/item?id=47755629

### 📰 원문 기사 요약
Countdown Timer Ultimate 플러그인의 wpos-analytics 모듈이 analytics.essentialplugin.com으로 연결되어 백도어 파일 wp-comments-posts.php를 다운로드했습니다. 이 파일은 wp-config.php에 PHP 코드를 삽입하여 악성 행위를 수행했습니다. WordPress.org 플러그인 팀은 문제 발생 후 플러그인을 2.6.9.1 버전으로 강제 업데이트하여 사태를 수습했습니다.

### 💬 Hacker News 토론 요약
Mythos와 같은 자동화된 취약점 발견 도구에 대한 과장된 반응에 대한 비판이 있습니다. 또한, npm install을 통해 수많은 라이브러리가 다운로드되는 상황에서 프로젝트 작성자가 모든 라이브러리의 내용을 파악하기 어렵다는 점이 지적되고 있습니다.

### 📌 종합 요약
30개의 WordPress 플러그인에 백도어가 심어진 사건이 발생했습니다. 플러그인 업데이트를 통해 문제가 해결되었지만, 이미 wp-config.php 파일이 변조되는 등 피해가 발생했습니다.

### 🔎 종합 핵심 포인트
- 공급망 공격을 통해 WordPress 플러그인에 백도어가 삽입되어 wp-config.php 파일이 변조되는 심각한 보안 문제가 발생했습니다.
- 자동화된 취약점 발견 도구의 효용성과 npm 패키지 관리의 복잡성에 대한 논의가 이루어지고 있습니다.
- 소프트웨어 공급망 보안의 중요성이 더욱 강조되고 있으며, 개발자는 사용하는 라이브러리에 대한 철저한 검토가 필요합니다.

**카테고리**: 보안/프라이버시

**태그**: WordPress, 플러그인, 백도어, 공급망 공격, 보안

---

## 2. [DaVinci Resolve – Photo](https://www.blackmagicdesign.com/products/davinciresolve/photo)
**Score**: 974 | **Comments**: 250 | **Rank Score**: 683.934
**작성자**: thebiblelover7 | **게시 시각(KST)**: 2026-04-14T11:25:15+09:00
**Hacker News 토론**: https://news.ycombinator.com/item?id=47760529

### 📰 원문 기사 요약
DaVinci Resolve의 Photo 페이지는 할리우드 수준의 색 보정 도구를 사진 편집에 도입했습니다. 화이트 밸런스, 노출, 기본 색상 조정과 같은 친숙한 도구 외에도, 노드 기반 워크플로우, Resolve FX, AI 도구, GPU 가속 등을 활용하여 기존 사진 편집 애플리케이션의 한계를 뛰어넘는 기능을 제공합니다. 특히, 퍼레이드, 웨이브폼, 벡터스코프, 히스토그램과 같은 전문적인 스코프를 통해 사진의 색감을 정밀하게 분석하고 조정할 수 있습니다.

### 💬 Hacker News 토론 요약
DaVinci Resolve의 강력한 색 편집 기능이 사진 편집에도 적용된 점에 대해 긍정적인 반응이 많습니다. 다만, Linux 플랫폼 지원이 미흡하다는 지적이 꾸준히 제기되고 있으며, Linux 환경에서의 안정적인 실행에 대한 개선 요구가 있습니다.

### 📌 종합 요약
Blackmagic Design의 DaVinci Resolve가 사진 편집 기능을 강화하여 새롭게 출시되었습니다. 기존의 강력한 색 보정 도구를 사진 편집 워크플로우에 통합하여, 전문가 수준의 색감 조정과 다양한 시네마틱 효과를 사진에도 적용할 수 있게 되었습니다.

### 🔎 종합 핵심 포인트
- DaVinci Resolve의 Photo 페이지는 사진 편집에 특화된 색 보정 도구와 AI 기반 기능들을 제공하여, 사진 편집 워크플로우를 혁신할 수 있다.
- Linux 플랫폼 지원 부족은 DaVinci Resolve의 사용자 경험을 저해하는 요인으로 작용하며, 개선이 필요하다.
- 전문가 수준의 색 보정 도구를 사진 편집에 활용함으로써, 사진 작가와 컬러리스트에게 새로운 창작 가능성을 제시한다.

**카테고리**: 개발 도구

**태그**: DaVinci Resolve, 사진 편집, 색 보정, AI, Linux

---

## 3. [GitHub Stacked PRs](https://github.github.com/gh-stack/)
**Score**: 858 | **Comments**: 481 | **Rank Score**: 602.687
**작성자**: ezekg | **게시 시각(KST)**: 2026-04-14T05:36:49+09:00
**Hacker News 토론**: https://news.ycombinator.com/item?id=47757495

### 📰 원문 기사 요약
GitHub Stacked PRs는 여러 개의 PR을 순서대로 정렬하여 한 번의 클릭으로 병합하는 기능입니다. 각 PR은 변경 사항의 특정 레이어를 나타내며, 독립적으로 검토된 후 함께 적용됩니다. 이를 통해 개발자는 복잡한 변경 사항을 작은 단위로 나누어 관리하고, 코드 리뷰어는 각 변경 사항에 집중하여 검토할 수 있습니다. 특히, 대규모 리팩토링이나 기능 추가 시 유용하며, 코드의 가독성과 유지보수성을 향상시키는 데 기여합니다.

### 💬 Hacker News 토론 요약
Stacked PRs 기능에 대해 Phabricator나 Mercurial의 stacked-diff 워크플로우와 비교하며 GitHub의 UI/UX 개선을 요구하는 의견이 있습니다. 반면, 개별 커밋 관리 UI 개선에 대한 요구도 있어, stacked PRs가 모든 개발자의 요구를 충족시키지는 못한다는 지적도 있습니다.

### 📌 종합 요약
GitHub에서 Stacked PRs 기능이 출시되어, 여러 PR을 순서대로 쌓아 한 번에 병합할 수 있게 되었습니다. 이 기능은 코드 변경을 체계적으로 관리하고 리뷰 효율성을 높이는 데 기여할 것으로 보입니다. 하지만 기존의 Phabricator나 Mercurial과 비교하며 UI/UX 개선을 요구하는 목소리도 있습니다.

### 🔎 종합 핵심 포인트
- GitHub Stacked PRs는 코드 변경을 레이어별로 관리하여 리뷰 효율성을 높이는 데 기여한다.
- 기존 stacked-diff 워크플로우를 사용하던 개발자들은 GitHub의 UI/UX 개선을 요구하고 있다.
- Stacked PRs 외에 개별 커밋 관리 UI 개선에 대한 요구도 존재한다.

**카테고리**: 개발 도구

**태그**: GitHub, PR, 코드 리뷰, 개발 워크플로우

---

## 4. [Backblaze has stopped backing up OneDrive and Dropbox folders and maybe others](https://rareese.com/posts/backblaze/)
**Score**: 782 | **Comments**: 484 | **Rank Score**: 549.985
**작성자**: rrreese | **게시 시각(KST)**: 2026-04-14T17:30:27+09:00
**Hacker News 토론**: https://news.ycombinator.com/item?id=47762864

### 📰 원문 기사 요약
개인 컴퓨터 백업용으로 Backblaze를 10년간 사용해 온 사용자가 Backblaze가 OneDrive와 Dropbox 폴더 백업을 중단한 사실을 발견했다. 과거에는 외부 하드 드라이브를 사용하여 데이터를 백업하다가 2015년부터 Backblaze의 무제한 저장 공간을 활용했다. 특히, 하드 드라이브 장애 발생 시 '하드 드라이브 배송 서비스'를 통해 데이터를 복구한 경험이 있어 Backblaze를 신뢰했지만, 이번 정책 변경으로 신뢰도가 하락했다.

### 💬 Hacker News 토론 요약
OneDrive나 Dropbox의 'Files On-Demand' 기능과 Backblaze 백업 방식의 충돌 가능성이 제기되고 있다. 일부 사용자는 Backblaze의 정책 변경에 실망하여 서비스 이탈을 고려하고 있으며, 다른 사용자는 클라이언트 앱 기반 백업의 한계점을 지적하며 대안을 모색하고 있다.

### 📌 종합 요약
Backblaze가 OneDrive 및 Dropbox 폴더 백업을 중단하면서 사용자들의 불만이 터져 나오고 있다. 백업 서비스의 정책 변경에 대한 명확한 고지가 없었던 점이 주된 문제로 지적되며, 사용자들은 서비스 신뢰성에 의문을 제기하고 있다.

### 🔎 종합 핵심 포인트
- Backblaze의 OneDrive 및 Dropbox 폴더 백업 중단은 사용자에게 사전 고지 없이 이루어져 혼란을 야기했다.
- 클라이언트 앱 기반 백업 방식은 'Files On-Demand'와 같은 클라우드 스토리지 기능과 충돌할 가능성이 있다.
- 이번 사례는 백업 서비스의 정책 변경 시 투명한 공지가 얼마나 중요한지를 보여준다.

**카테고리**: 인프라/클라우드

**태그**: Backblaze, 백업, 클라우드 스토리지, OneDrive, Dropbox

---

## 5. [A new spam policy for “back button hijacking”](https://developers.google.com/search/blog/2026/04/back-button-hijacking)
**Score**: 745 | **Comments**: 441 | **Rank Score**: 523.832
**작성자**: zdw | **게시 시각(KST)**: 2026-04-14T12:06:27+09:00
**Hacker News 토론**: https://news.ycombinator.com/item?id=47760764

### 📰 원문 기사 요약
Google은 사용자가 브라우저의 '뒤로 가기' 버튼을 클릭했을 때 이전 페이지로 돌아가는 기대감을 깨는 '뒤로 가기 버튼 하이재킹' 행위를 스팸 정책 위반으로 간주합니다. 이는 사용자의 브라우저 탐색을 방해하고, 예기치 않은 광고나 페이지로 이동시켜 사용자 경험을 저해하는 악성 행위입니다. Google Search Essentials에 따라 이러한 기만적인 행위를 금지하며, 사용자들은 이러한 조작으로 인해 불쾌감을 느끼고 웹사이트 방문을 꺼리게 됩니다. 따라서 Google은 사용자 경험을 최우선으로 고려하여 이번 정책을 강화했습니다.

### 💬 Hacker News 토론 요약
사용자들은 웹사이트의 키보드 단축키 설정을 제한하는 브라우저 기능의 필요성을 제기하며, 특정 페이지가 브라우저 기록을 수정하는 것을 막는 Firefox의 about:config 설정과 같은 클라이언트 측 해결책을 제시합니다.

### 📌 종합 요약
Google이 '뒤로 가기 버튼 하이재킹'을 명시적인 스팸 정책 위반으로 규정하고, 사용자 경험을 저해하는 행위에 대한 제재를 강화합니다. 브라우저의 뒤로 가기 버튼을 조작하여 사용자를 원치 않는 페이지로 이동시키는 행위를 근절하려는 조치이며, 사용자들은 브라우저 기능 악용에 대한 불만을 표하고 있습니다.

### 🔎 종합 핵심 포인트
- Google이 '뒤로 가기 버튼 하이재킹'을 스팸 정책 위반으로 명시하여 사용자 경험 보호를 강화했다.
- 사용자들은 웹사이트가 브라우저 기능을 임의로 변경하는 행위에 대한 제어 권한 강화를 요구하고 있다.
- 브라우저 설정 변경을 통해 일부 사용자들은 '뒤로 가기 버튼 하이재킹'에 대한 자체적인 해결책을 모색하고 있다.

**카테고리**: 정책/사회 이슈

**태그**: spam, browser, ux, google, policy

---

## 6. [Nothing Ever Happens: Polymarket bot that always buys No on non-sports markets](https://github.com/sterlingcrispin/nothing-ever-happens)
**Score**: 459 | **Comments**: 260 | **Rank Score**: 322.991
**작성자**: m-hodges | **게시 시각(KST)**: 2026-04-14T00:31:06+09:00
**Hacker News 토론**: https://news.ycombinator.com/item?id=47753472

### 📰 원문 기사 요약
해당 봇은 Polymarket의 예측 시장에서 스포츠 외 이벤트에 대해 'No' 포지션을 자동으로 구매하는 방식으로 작동한다. 구체적인 기술 스택이나 알고리즘은 명시되지 않았지만, Polymarket API를 활용하여 자동 거래를 수행하는 것으로 추정된다.

### 💬 Hacker News 토론 요약
일부 사용자는 수익성이 없는 프로젝트라는 점을 지적하며 회의적인 반응을 보이는 반면, 다른 사용자는 재미있는 실험이라는 긍정적인 반응을 보이고 있다. 스포츠 시장에 적용 가능성에 대한 의견도 제시되었다.

### 📌 종합 요약
Polymarket에서 스포츠 외 시장에 대해 항상 'No'를 구매하는 봇에 대한 논의가 Hacker News에서 활발하게 진행 중이다. 이 봇은 수익을 목표로 하지 않고 재미를 위한 프로젝트로 보이며, 스포츠 시장에는 적용하기 어렵다는 의견도 있다.

### 🔎 종합 핵심 포인트
- Polymarket API를 이용한 자동 거래 봇 개발
- 예측 시장에서 'No' 포지션 자동 구매 전략의 타당성
- 자동 거래 봇의 윤리적, 법적 문제 발생 가능성

**카테고리**: AI/ML

**태그**: Polymarket, 자동 거래, 예측 시장, 봇, AI

---

## 7. [jj – the CLI for Jujutsu](https://steveklabnik.github.io/jujutsu-tutorial/introduction/what-is-jj-and-why-should-i-care.html)
**Score**: 416 | **Comments**: 355 | **Rank Score**: 293.778
**작성자**: tigerlily | **게시 시각(KST)**: 2026-04-14T19:33:39+09:00
**Hacker News 토론**: https://news.ycombinator.com/item?id=47763759

### 📰 원문 기사 요약
제공된 외부 기사 발췌 내용이 없어 요약할 수 없습니다. Jujutsu CLI 도구에 대한 기술 스택, 알고리즘, 아키텍처적 특징 등의 정보가 필요합니다.

### 💬 Hacker News 토론 요약
HTTPS를 통한 jj 저장소 제공 방식에 대한 문의가 있었으며, Git과 비교하여 더 나은 또는 동등한 솔루션이 있는지에 대한 논의가 진행 중입니다. 또한, jj가 특정 개발자들에게 중요한 이유에 대한 의견도 제시되었습니다.

### 📌 종합 요약
Jujutsu(jj)는 Git을 대체할 수 있는 새로운 CLI 도구입니다. 이 도구는 HTTPS를 통한 저장소 제공 방식과 기존 Git과의 호환성 측면에서 활발한 논의를 불러일으키고 있습니다.

### 🔎 종합 핵심 포인트
- Jujutsu CLI 도구의 HTTPS 저장소 제공 방식 및 Git과의 호환성
- jj가 특정 개발자들에게 어떠한 가치를 제공하는가
- 기존 Git 워크플로우를 대체할 수 있을지에 대한 잠재력

**카테고리**: 개발 도구

**태그**: CLI, Jujutsu, Git, 버전 관리

---

## 8. [Lean proved this program correct; then I found a bug](https://kirancodes.me/posts/log-who-watches-the-watchers.html)
**Score**: 359 | **Comments**: 163 | **Rank Score**: 253.222
**작성자**: bumbledraven | **게시 시각(KST)**: 2026-04-14T09:25:08+09:00
**Hacker News 토론**: https://news.ycombinator.com/item?id=47759709

### 📰 원문 기사 요약
저자는 Lean을 사용하여 프로그램의 정확성을 증명했지만, 이후 오버플로우 버그를 발견했습니다. 이 버그는 64비트 정수를 32비트 정수로 잘못 캐스팅하여 발생했습니다. 형식적 검증은 코드의 구현이 사양을 준수하는지 확인하지만, 사양 자체가 정확한지는 보장하지 않습니다. 저자는 사양의 정확성을 보장하기 위해 추가적인 노력이 필요하다고 강조합니다.

### 💬 Hacker News 토론 요약
일부에서는 Lean으로 검증된 코드에서 버그가 발견되었다는 제목에 의문을 제기하며, 실제로는 검증된 코드 자체가 아니라 사양의 문제였다는 점을 지적합니다. 다른 사용자들은 사양 오류의 일반적인 경험을 공유하며, 형식적 검증이 사양의 정확성을 담보하지 않는다는 점을 강조합니다.

### 📌 종합 요약
Lean으로 검증된 프로그램에서 버그를 발견한 경험에 대한 글입니다. 형식적 검증이 완벽한 소프트웨어를 보장하지 못하며, 사양 자체의 오류 가능성을 시사합니다.

### 🔎 종합 핵심 포인트
- 형식적 검증은 코드 구현의 정확성을 보장하지만, 사양 자체의 오류는 잡아내지 못한다.
- 사양 오류는 오버플로우와 같이 예상치 못한 방식으로 나타날 수 있다.
- 소프트웨어 개발 시 사양의 정확성을 검증하기 위한 추가적인 노력이 필요하다.

**카테고리**: 개발 도구

**태그**: Lean, 형식적 검증, 버그, 사양 오류, 소프트웨어 개발

---

## 9. [Rare concert recordings are landing on the Internet Archive](https://techcrunch.com/2026/04/13/thousands-of-rare-concert-recordings-are-landing-on-the-internet-archive-listen-now/)
**Score**: 339 | **Comments**: 97 | **Rank Score**: 239.624
**작성자**: jrm-veris | **게시 시각(KST)**: 2026-04-14T22:46:31+09:00
**Hacker News 토론**: https://news.ycombinator.com/item?id=47765604

### 📰 원문 기사 요약
Block Club Chicago의 원문 기사에 따르면, 인터넷 아카이브에 업로드된 자료 중에는 초기 Nirvana 공연을 비롯해 다양한 희귀 음원들이 포함되어 있다. 특히, 음향 엔지니어링 기술 발전 덕분에 과거에는 듣기 힘들었던 고품질의 라이브 음원을 접할 수 있게 되었다. 이러한 자료들은 음악 역사 연구는 물론, 당시 사회 문화적 배경을 이해하는 데에도 중요한 역할을 할 것으로 기대된다.

### 💬 Hacker News 토론 요약
한 사용자는 자신이 90년대에 녹음한 콘서트가 부틀렉으로 유통되고 있다고 언급하며, 자신의 경험을 공유했다. 또 다른 사용자는 원문 기사가 더 흥미롭다는 의견을 제시하며 추가 링크를 제공했다.

### 📌 종합 요약
희귀 콘서트 녹음 자료들이 인터넷 아카이브에 올라오고 있다는 소식이다. 90년대 녹음 자료부터 초기 Nirvana 공연까지 다양한 자료가 공유되면서 음악 팬들의 관심이 집중되고 있다.

### 🔎 종합 핵심 포인트
- 희귀 콘서트 녹음 자료들이 인터넷 아카이브를 통해 공유되면서 과거 음원 접근성이 향상되었다.
- 사용자들은 자신의 녹음 경험을 공유하며, 부틀렉 유통에 대한 다양한 의견을 제시하고 있다.
- 인터넷 아카이브는 음악 역사 연구 및 사회 문화적 배경 이해에 기여할 수 있는 중요한 자료를 제공한다.

**카테고리**: 기타

**태그**: 음악, 인터넷 아카이브, 콘서트, 녹음, Nirvana

---

## 10. [Building a CLI for all of Cloudflare](https://blog.cloudflare.com/cf-cli-local-explorer/)
**Score**: 323 | **Comments**: 106 | **Rank Score**: 227.532
**작성자**: soheilpro | **게시 시각(KST)**: 2026-04-14T00:44:02+09:00
**Hacker News 토론**: https://news.ycombinator.com/item?id=47753689

### 📰 원문 기사 요약
Cloudflare는 전체 플랫폼을 아우르는 CLI 도구를 개발 중입니다. 이를 통해 개발자들은 Cloudflare의 다양한 서비스와 기능을 명령 줄에서 직접 관리할 수 있게 됩니다. 특히 Wrangler CLI를 통해 로컬 개발 환경에서 필요한 API 토큰 권한을 미리 확인할 수 있도록 개선될 예정입니다.

### 💬 Hacker News 토론 요약
사용자들은 Cloudflare CLI에 대한 기대감을 표하면서도, 권한 관리의 중요성을 강조하고 있습니다. 특히 리소스 그룹별 권한 설정을 통해 실수로 인한 프로덕션 환경의 문제를 방지해야 한다는 의견이 제시되고 있습니다.

### 📌 종합 요약
Cloudflare 전체를 제어할 수 있는 CLI(명령 줄 인터페이스) 개발에 대한 소식입니다. 사용자들은 CLI에 대한 기대와 함께 권한 관리 및 리소스 그룹 기능 추가에 대한 요구를 제시하고 있습니다.

### 🔎 종합 핵심 포인트
- Cloudflare 전체를 제어하는 통합 CLI 개발이 진행 중이다.
- 사용자들은 CLI를 통해 API 토큰 권한을 사전에 확인하고 싶어한다.
- 리소스 그룹별 권한 관리 기능 추가를 통해 안정성을 확보해야 한다는 요구가 있다.

**카테고리**: 인프라/클라우드

**태그**: Cloudflare, CLI, API, 권한 관리, 리소스 그룹

---

