# winterrdog@x86_64

# ...^_^...

# 46_68x@godrretniw


	.text
	.global main
	main:
		# godrretniw
		movl $intro_len, %edx
		leaq intro(%rip), %rsi
		movq $0x1, %rdi
		movq $0x1, %rax
		syscall

		movl $interest_len, %edx
		leaq interest(%rip), %rsi
		movq $0x1, %rdi
		movq $0x1, %rax
		syscall

		movl $earth_realm_role_len, %edx
		leaq earth_realm_role(%rip), %rsi
		movq $0x1, %rdi
		movq $0x1, %rax
		syscall

		movl $future_prospects_len, %edx
		leaq future_prospects(%rip), %rsi
		movq $0x1, %rdi
		movq $0x1, %rax
		syscall

		movl $location_len, %edx
		leaq location(%rip), %rsi
		movq $0x1, %rdi
		movq $0x1, %rax
		syscall

		movl $getting_remote_access_len, %edx
		leaq getting_remote_access(%rip), %rsi
		movq $0x1, %rdi
		movq $0x1, %rax
		syscall

		movq $0x3c, %rax
		movq $0xff, %rdi
		syscall

	intro:
		.ascii "[INFO] Hey! winterrdog found!\n"
		intro_len = . - intro

	interest:
		.ascii "[INFO] I’m interested in infosec and Python/C/C++/Assembly/Rust programming. But lately I've been diving into Golang."
		interest_len = . - interest

	earth_realm_role:
		.ascii "[INFO] I’m doing penetration testing, malware development & reverse engineering :) \n"
		earth_realm_role_len = . - earth_realm_role

	future_prospects:
		.ascii "[INFO] I’m looking forward to collaborate on any C++/C or Rust or Python projects\n"
		future_prospects_len = . - future_prospects

	location:
		.ascii "[DEBUG] EARTH REALM\n"
		location_len = . - location

	getting_remote_access:
		.ascii "[CRITICAL] How to reach me winterrdog@keemail.me or mayaoffsetmatrix@gmail.com or winterrdog@protonmail.ch or https://t.me/winterrdog\n"
		getting_remote_access_len = . - getting_remote_access


# 🤔 => 😕 => 😖;

# Calm down!💆😌

In order to make sense out of this( if you know how to get this information, then u r not a skiddie 🤝 )

But if u do not, please use one of these online assemblers:

https://www.jdoodle.com/compile-assembler-gcc-online/

https://www.onlinegdb.com/online_gcc_assembler

😅At least you learnt something NEW today😎!(How to make assembly code executable - though this is just for Intel/AMD)

# Whatever you'll get as output is the info about me! Thanks for passing by folks😊.

<!---
winterrdog/winterrdog is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
