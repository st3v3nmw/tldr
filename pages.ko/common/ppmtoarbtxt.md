# ppmtoarbtxt

> PPM 이미지를 템플릿에 따라 임의의 텍스트 형식으로 변환.
> 더 많은 정보: <https://netpbm.sourceforge.net/doc/ppmtoarbtxt.html>.

- 주어진 템플릿에 따라 PPM 이미지를 텍스트로 변환:

`ppmtoarbtxt {{경로/대상/템플릿}} {{경로/대상/이미지.ppm}} > {{경로/대상/출력_파일.txt}}`

- 주어진 템플릿에 따라 PPM 이미지를 텍스트로 변환하고, 지정한 헤드 템플릿의 내용을 앞에 추가:

`ppmtoarbtxt {{경로/대상/템플릿}} -hd {{경로/대상/헤드_템플릿}} {{경로/대상/이미지.ppm}} > {{경로/대상/출력_파일.txt}}`

- 주어진 템플릿에 따라 PPM 이미지를 텍스트로 변환하고, 지정한 테일 템플릿의 내용을 뒤에 추가:

`ppmtoarbtxt {{경로/대상/템플릿}} -hd {{경로/대상/테일_템플릿}} {{경로/대상/이미지.ppm}} > {{경로/대상/출력_파일.txt}}`

- 버전 표시:

`ppmtoarbtxt -version`
