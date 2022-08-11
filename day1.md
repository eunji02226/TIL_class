# 8. String Text file
- split()
  - split(maxsplit=숫자)
> ex)
> ~~~python
> phone_number = "+82-10-1234-5678"
> split_num=phone_number.split("-",1)
> print(split_num)
> print("국내전화번호: {0}".format(split_num[1]))

- strip()
  - lstrip()
  - rstrip()
> ex) 
> ~~~python
> TBZ_member_str=" M, J ,BB ,S, Q"
> TBZ_list=[]
> for TBZ in TBZ_member_str:
> temp = TBZ.strip()
> TBZ_list.append(temp)
> print(TBZ_list)
> ~~~
- str.replace(기존문자,바꿀문자,횟수)
  > ex)
  ~~~python
  str="Python is powerful. Python is easy to learn. Python is open"
  print(str.replace("Python","python"))
  print(str.replace("Python","python",2))
  ~~~
- 기타 메소드
> ex)
> ~~~python
> print(str.find("Python",10,30))
> print(str.find("Python",35))
> print("Python의 갯수?", str.count("Python"))
> print("powerful의 갯수?", str.count("powerful"))
> print("Python으로 시작?", str.startswith("Python"))
> print("is으로 시작?", str.startswith("is"))
> print(".으로 시작?", str.endswith("."))
> ~~~
