* 1.profile = {name:'kk', age: 18}�A�аݡG
p profile["name"]
�|�o�줰�򵲪G? ������?
```
�o��nil
profile�̭���name�Osymbol
��"name"���P
```
* 2.�мg�@�q Ruby �{���AŪ���ɮ� homework-03-31-content.txt �����e�A�b�C�@�檺�e���[�W�渹�A���o�ˡG
1 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam imperdiet
2 quis arcu in tincidunt. Aliquam viverra mauris sed lorem pretium, eget
3 interdum ante pulvinar. Nullam iaculis molestie leo eu fringilla. Praesent
4 vitae commodo dui. Vivamus non urna a libero faucibus imperdiet non
5 vestibulum nulla. Maecenas vel tellus tellus. Praesent lacinia ac ipsum
6 quis lacinia. Praesent malesuada massa a semper fermentum. Nunc at elit
7 sapien. Donec molestie ac urna non varius.
8
9 Etiam efficitur purus a congue auctor. Nullam nec nisl nec est mollis
10 suscipit quis in ex. Aenean et urna est. Praesent fringilla augue ut ipsum
11 feugiat fermentum. Nulla pharetra erat sed sodales facilisis. Nulla eget
12 cursus elit. Quisque sit amet mi leo. Praesent posuere pulvinar massa,
13 fringilla pellentesque leo ornare vel. Sed vel quam varius, rutrum sem
14 ullamcorper, faucibus purus. Fusce finibus diam vitae convallis posuere.
15 Donec lacinia placerat dui in venenatis.
�åB�⵲�G��X�� result.txt�C
```
output = ""
line = 0
File.open("homework-03-31-content.txt","r") do |f|
    f.each_line do |L|
        print line+=1
        puts " #{L}"
        output+=line.to_s + " #{L}"
    end
end
line = 0
File.open("result.txt","w") do |g|
    g << output
end
```
* 3.�мg�@�q Ruby �{���A�p���ɮ� homework-03-31-content.txt �����X�Ӧr�����׬O�p��ε��� 5 �Ӧr���C
```
```
```
