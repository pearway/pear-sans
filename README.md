# Pear Sans

![Pear Sans specimen](documentation/pear-sans-specimen.png)

Pear Sans (페어산스) is a geometric Hangul sans serif in the spirit of the Bauhaus. Its skeleton is built from circles and straight lines, with handwriting and ornament stripped away, so each letter is drawn with the fewest strokes it needs and reads clearly.

The family comes in 7 weights from Thin to Bold, and as a variable font with a weight axis (100 to 700). It covers all 11,172 modern Hangul syllables, the Google Fonts Latin Core character set, figures and punctuation.

Designed by Heebae Lee (Pear Type Foundry).

## Building

Fonts are built with [gftools builder](https://github.com/googlefonts/gftools):

```
python3 -m venv venv
. venv/bin/activate
pip install -r requirements.txt
cd sources
gftools builder config.yaml
```

The built fonts are written to `fonts/variable` and `fonts/ttf`.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1. See [OFL.txt](OFL.txt).

## 페어산스

원과 직선으로 뼈대를 짜고 필체와 장식을 덜어낸 기하학 한글 산스예요. 최소한의 획으로 또렷하게 읽혀요. Thin부터 Bold까지 7가지 굵기와 가변 폰트, 한글 11,172자와 라틴 문자를 지원해요. SIL 오픈 폰트 라이선스 1.1로 누구나 자유롭게 쓸 수 있어요.
