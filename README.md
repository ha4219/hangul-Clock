<h1 align="center">
    <a href="https://github.com/ha4219/hangul-clock"/>
    hangul-clock
</h1>






## Contents

- [Title](#-title)
- [Brochure](#-brochure)
- [Skill](#-skill)
- [Example](#-example)
- [Report](#-report)
- [License](#-license)



 

## 🎉 Title

> HANGUL-CLOCK

## 🪧 Brochure
![Poster](https://github.com/ha4219/hangul-clock/blob/main/assets/18101269_poster.png?raw=true)

> Logisim으로 구현한 한글 시계입니다.
## 💡 Skill

- <b>Logisim Evolution</b>
![logisim-evolution_image](https://github.com/logisim-evolution/logisim-evolution/raw/master/docs/img/logisim-evolution-logo.png)



## 📱 Example

![example](https://github.com/ha4219/hangul-clock/blob/main/assets/18101269.gif?raw=true)
- [youtube](https://www.youtube.com/watch?v=cNpm3_mCp18)



## 📋 report

### 😁 프로젝트 구조
- 시계 구현
- 한글 display로 변환

### 🙈 프로젝트 수행 중 만난 문제

- 이전에 배운 실습 내용을 기초로 작성하려고 하니 내용이 많았지만, 차근차근 해결했습니다.
1. 시계의 분, 시간을 변경할 수 있는 부분을 PulseSwitch라는 component로 관리했지만, clock의 주파수가 작을 경우 해당 변환이 잘 이루어지지 않았습니다.
    > 해결 방법으로 주파수를 빠르게 변환하든가 아니면 기존 시계 로직의 주파수를 빠르게 해야 했는데 이 부분은 아이디어가 안 떠올라 해결하지 못했습니다.
2. 한글 디스플레이 변환 문제
    > 처음에는 현재 존재하는 font를 기준으로 이것을 bitmap으로 변환하려고 8x8 bitmap으로 변환해서 보여주려고 했습니다. 그래서 실제 한글을 캡쳐해서 8x8로 resize해서 matrix의 value를 확인해 변환했지만, 이는 글자의 형태가 이상해서 직접 하나하나 그려서 문제를 해결했습니다.

### 🚀 프로젝트 수행 중 새롭게 배운 점
- > 이전에 실습했던 것 처럼 4bit-counter, 4bit-comparator 등을 구현하면서 진행했는데 Logisim에서 제공하는 회로가 많았습니다. 처음에는 직접 구현하면서 진행했지만, logisim에서 제공하는 회로를 이용하니 시간을 많이 단축할 수 있었습니다.


### 📖 프로젝트를 수행하며 느낀 점
- > 프로그램을 사용해서 만들어서 컴퓨터로 간단히 할 수 있었지만 직접 회로도 만들어보고 싶었고 3학년 1학기 수업인 시스템 프로그래밍과 같이 공부하고 있어서 그런지 cpu 연산에 대해 깊이 있게 이해할 수 있었습니다. 추후 Hour, Miniute set 부분과 display를 (8x8) LED Matrix를 36(6x6)개를 둬서 구성했는데 이를 한 LED Matrix에 구성하고 더 나아가 색도 추가해서 결과를 내고 싶습니다.

## 📄 License
This Project is MIT licensed, as found in the LICENSE file.