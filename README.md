## Solidity
- 솔리디티(Solidity)는 계약 지향 프로그래밍 언어로 다양한 블록체인 플랫폼의 스마트 컨트랙트 (Smart Contract) 작성 및 구현시 사용.
- 2014년 8월에 Gavin Wood 가 처음으로 제안했으며, 제안 이후 이더리움 프로젝트의 Christian Reitwiessner 가 이끄는 솔리디티팀에 의해 개발.
- Solidity is statically typed, supports inheritance, libraries and complex user-defined types among other features.
- Ethereum Virtual Machine(EVM)을 목표로 설계된 4가지 언어 중 하나이다.(Serpent, LLL, Viper (실험용) ) 
- 현재는 솔리디티가 이더리움 주요 언어.
- 정적타입(statically-typed) 언어
- ECMAScript 문법 기반 
- EVM상에서 작동하는 스마트컨트랙트를 개발하기 위해 설계
- EVM에서 작동 가능핚 바이트코드로 컴파일 됨.
- 개발자는 솔리디티를 통해서 스스로 실행되는 비즈니스 로직을 스마트컨트랙트에 담아서 Application을 구현할 수 있음.


## 스마트컨트랙트 작성 및 배포 순서
1. 스마트컨트랙트코딩
- 구현하고자하는내용을Solidity 언어로코딩.
2. 구현할 소스코드 컴파일
- 컴파일결과 EVM 바이트코드 생성됨.
3. 스마트컨 트랙트 배포
- 스마트컨트랙트를 배포하는것은 컴파일된 EVM 코드를하나의 트랜잭션처럼 블록에 추가시켜 블록체인에 등록시키는 작업.
- 소스컴파일 -> EVM 바이트코드 -> 구체적인 작업은 ABI(Application Binary Interface) 취득 -> ABI로부터 컨트랙트객체 생성 -> 트랜잭션 생성하여 블록에추가
- 채굴자가 해당블록을 채굴하게되면 블록체인에 포함됨

## Dependencies
+ Solidity 참조 https://solidity.readthedocs.io/
+ 브라우저 기반 통합 IDE https://remix.ethereum.org/
+ TestRPC용도 - Ganache https://www.trufflesuite.com/ganache
