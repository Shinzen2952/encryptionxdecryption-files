# encryptionxdecryption-files

#account_for_encryptedfiles



def check_email_password():
    while True:
        try:
            email = input("Enter your email here: ").lower()
            password = int(input("Enter the coded password here: "))

            if email == "shikisenri123":
                if password == 123456789:
                    return True
            else:
                print("input a wrong credentials, please try again")

        except Exception as e:
            print("the wrong is :", e)

if check_email_password() == True:
    f = open("C:\\Users\\ADMIN\Desktop\\vtube applications\\myfile.txt")
    print(f.read())
else:
    print("wrong credentials (X)")


