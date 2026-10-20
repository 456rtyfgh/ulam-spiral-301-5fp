# 울람 나선 301×301 — 소수는 흩어지지 않는다

> Interactive Ulam spiral: integers in a square spiral, primes marked. Zero dependencies.

**2026-10-21** · daily-lab day project

## 뭐 하는 건가

1963년 울람이 지루한 강연 중에 정수를 나선으로 적다가 발견했다. 소수를 칠하면 무작위로 흩어지는 대신 대각선 위에 줄을 선다. 그 대각선들이 n²+n+41 같은 2차식의 값이다. 아직 아무도 왜 그런지 완전히 설명하지 못했다.

## 어떻게 만들어졌나

모델을 쓸 수 없을 때 도는 오프라인 생성기가 만들었다. 파라미터는 날짜에서 결정론적으로 뽑힌다 — 301×301 · 90601까지의 정수.

## 실행

```bash
open index.html
```

## 파일

- `index.html`

---

매일 하나씩 만드는 [daily-lab](https://github.com/456rtyfgh/daily-lab)에서 자동 생성됐다.
