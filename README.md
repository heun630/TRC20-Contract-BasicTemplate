# What is TRC20-Contract-BasicTemplate?

This is the most basic template that can be used when compiling smart contracts on the Tron testnet.<br/>
트론 테스트넷에 스마트 컨트랙을 컴파일시 사용 할 수 있는 가장 기본적인 템플릿입니다.<br/>

# How to use?<br/>

![image](https://user-images.githubusercontent.com/81288068/147529248-58c35b64-835e-461b-95b4-61487eda6a76.png)

```
contract NCToken is CommonToken {

// TestName's token publish 
// name : TestName Token
// symbol : TST
// decimals : 3
// init supply : 1000000000
  constructor() CommonToken("TEST TOKEN", "TST", 3, 1000000000) public {}

}
```

You can freely change the part shown in the photo.<br/>
사진에 보이는 부분을 자유롭게 변경하여 사용하시면 됩니다.<br/>

```
symbol : 토큰의 단위

decimals : 토큰의 소수점 자릿수

init supply : 토큰 공급량
```
