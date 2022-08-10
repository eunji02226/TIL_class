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
- 
