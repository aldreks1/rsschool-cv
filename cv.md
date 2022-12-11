
# Artem Fateev

## Contacts

telegram: https://t.me/aIdreks
discord: let's dye this world#2490
GitHub: https://github.com/aldreks1
email: cloneartem@mail.ru


## Information:

  
I'm 19 years old. I am a 3rd year student at the Faculty of Radiophysics and Computer Technology at Belarusian State University. I have not yet had a chance to work in the IT field, but I aspire to this. My main goal in the it sphere is that I want to bring something new and simplify our world.


## Skills
c++ 
html
oop
git
VS
VS code
Assembly
##  Code example 

```Assembly
.386
.model flat, stdcall
.stack 4096

.data

k DWORD 4
l DWORD 3
m DWORD 5
n DWORD 2

lbs BYTE 1 ;ладья бьет слона
sbl BYTE 1 ;слон бьет ладью

isUnderAttack BYTE 0

ExitProcess proto, dwExitCode:dword

.code
main proc

;проверяем ладью
mov eax, k
cmp eax, m
jne skip1
mov sbl, 0

skip1:
	mov eax, l
	cmp eax, n
	jne skip2
	mov sbl, 0

skip2: ;проверяем слона
; eax = |x1-x2|
	mov eax, k
	sub eax, m
	imul eax

; ebx = |y1-y2|
	mov ebx, l
	sub ebx, n
	imul ebx, ebx

	cmp eax, ebx
	je a
	jmp endOfIf
a:
	mov lbs, 0

endOfIf:
invoke ExitProcess,0

main endp
end main
```
##  Work experience
not yet
## Education
  
I graduated from the Gomel city lyceum, and entered the higher educational institution, which I spoke about in my information about myself
  
## English level
A2+( based on the test results from epam)