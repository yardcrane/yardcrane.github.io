## 서비스

데브옵스(DevOps)는 개발(Development)과 운영(Operation)의 조합어 입니다. 개발 방식과 운영 방식의 차이점 속에서 개발팀과 운영팀의 협업을 이끌어 내기 위한 프렉티스가 데브옵스입니다. 데브옵스를 위해 애플리케이션 아키텍처가 기존의 모놀리틱 아키텍처와 달라지게 됩니다. 데브옵스를 위한 아키텍처는 작은 변경 사항이 수시로 배포될 수 있어야 하고, 변화에 대한 품질이 확실히 보장이 되어야 합니다.

이를 위한 아키텍처를 위한 원칙이 있습니다. 각 팀간 관심사는 명확히 분리가 되어야 합니다. 관련 기능이 밀접하게 응집이 되어야 하고, 모모듈간 의존성은 낮게 잡아야 합니다.

마이크로 서비스는 3-티어 패턴의 로직 티어를 작은 서비스들로 쪼개어 프로그램 언어에 구애받지 않는 프로토콜로 서로 통신합니다. 주로 HTTP 기반의 JSON REST 프로토콜을 사용합니다.

서비스들이 잘게 분리되었으니 배포는 독자적으로 이루어 지게 되어 지속적 배포 (Continuous Delivery) 가 가능해 집니다.

비즈니스 영역을 작은 서비스로 쪼개며 데이타 영역 또한 분리가 가능합니다. 전통적인 방식의 데이타 설계 방식과 달라 찬성과 반대 의견이 갈리나 데이타 영역이 나뉘어 지면 데이타 모델링이 간소해 집니다.

## 인프라 - 클라우드 서비스
### 2-1 IGW ( Internet Gateways )
IGW는 수평확장 가능하고, 이중화 가능한 고가용성의 VPC 컴포넌트로 인터넷과 사용중인 VPC 인스턴스와의 통신을 허용해 줍니다.

네트웤 주소 변환(NAT)과 VPC 내의 목적지 주소로 보내주는 역할을 합니다.

### 2-2 WAF ( Web Application Firewall ) 
웹애플리케이션 방화벽

### 2-3 Route53
가용성과 확장성이 우수한 DNS(도메인 이름 시스템) 웹 서비스

### 2-4 Amazon CloudFront
짧은 지연 시간과 빠른 전송 속도로 웹 콘텐츠를 사용자에게 안전하게 전송하는 글로벌 CDN(콘텐츠 전송 네트워크)입니다. 

### 2-5 ALB ( Application Load Balancer )
Contents 기반 라우팅 기능을 제공합니다. 가중치를 기반한 로드밸런싱이 가능합니다.

### 2-6 Web Proxy 
STON Edge Server의 주요 기능은 다음과 같습니다.

가상 호스트 관리
URL 전처리 ( URL Rewrite )
캐싱
트래픽 모니터링
### 2-7 Amazon S3
### 2-8 EKS
### 2-9 MSK
### 2-10 Elasticache
### 2-11 ElasticSearch

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/yardcrane/yardcrane.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
