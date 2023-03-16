# instance
Java 인스턴스
## 인스턴스란?<br>
인스턴스란 클래스를 통해서 구현해야할 대상(객체)이 실제로 구현된 구체적인 실체를 말한다.<br>
## 개념
1) 클래스 - 1,2,3단계 모두 포함<br>
2) 생성자 - 3단계에만 사용<br>
3) 인스턴스 - 2,3단계에서 사용<br>
4) 매개변수 - 3단계에서만<br>
5) this - 3단계에서만<br>
## 첫번째 instance
Accounting을 만들어 Value of supply, VAT, Total를 선언함.<br><br>
![image](https://user-images.githubusercontent.com/126844692/225491517-ac00e859-7c12-48a8-93ff-7e410687437a.png)<br>
## 두번쨰 instance
Accounting의 복제품을 만들고 static double에서 double을 지운다음 valueOFSupply와 getVAT를 만들어 Value of supply, VAT, Total를 선언함.<br><br>
![image](https://user-images.githubusercontent.com/126844692/225491875-17859a50-db39-4edf-ac49-302e339d84e5.png)<br>
## 세번쨰 instance
public Accounting3(double valueOfSupply)를 추가하고 Accounting의 복제품 괄호 안에 숫자를 입력해 선언함.<br><br>
![image](https://user-images.githubusercontent.com/126844692/225491932-438a5437-a6ed-4e85-af25-90e860a7cb64.png)<br>
