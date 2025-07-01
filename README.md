# 7일차

### 파이썬 기초 융합
리스트로 딕셔너리를 묶어 관리하는게 좋은 코드다
```python
obstacles = [ {"x": 0, "y": 2, "type": "wall"},
              {"x": 1, "y": 3, "type": "tree"},
              {"x": 2, "y": 4, "type": "rock"} ]
```
x좌표 딕셔너리를 다시 리스트로 꺼내오고, 딕셔너리끼리 좌표비교함.
```python
if {'x':x+1} in [{'x':o['x']} for o in obstacles]:
```

### 함수 예제들 9문제
1. https://claude.ai/public/artifacts/ecfa16b4-2106-4e7b-a637-a17f20eb3126
2. https://claude.ai/public/artifacts/2bacfb57-fa54-46bf-bd52-f4d858b045a4
3. https://claude.ai/public/artifacts/0bd88961-bc8c-43b4-b40b-aa0a27fe96df
4. (4번은 3번의 좌우방향만 다른 버전이라 링크는 없다.)
5. https://claude.ai/public/artifacts/0071fea5-0417-4ac3-b753-5e47ea108c2a
6. https://claude.ai/public/artifacts/27051f81-4a36-4075-8d2b-ec7199d9a7fb
7. https://claude.ai/public/artifacts/13112488-2160-4216-8845-4187a58f746c
8. https://claude.ai/public/artifacts/6ddac9ec-2dba-456b-bb09-bf6e277a8a06
9. https://claude.ai/public/artifacts/76eafd8d-4d90-437d-be19-5bf67c275500
