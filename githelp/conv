txt = input("Enter Text: ")

def namee(txtt):
    nameee =[]
    for j in txtt:
        if j==']':
            break
        else:
            nameee.append(j)
    return ''.join(nameee)

def link(txttt):
    linkk = []
    for k in txttt:
        if k ==']':
            continue
        elif k=='(':
            continue
        elif k==')':
            break
        else:
            linkk.append(k)
    return ''.join(linkk)

name = namee(txt[2:])
for i in range(len(txt)):
    if txt[i]==']':
        lin = link(txt[i:])
    else:
        continue
print("<img src=\""+lin+"\" alt=\""+name+"\"/>")
