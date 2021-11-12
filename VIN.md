shortVIN = 776544995

data = [int(x) for x in str(shortVIN)]
ihelp[0] = data[0]*10 + data[1]
ihelp[1] = data[2]*10 + data[3]
ihelp[2] = data[4] + 48
ihelp[3] = data[5] + 48
ihelp[4] = data[6] + 48
ihelp[5] = data[7] + 48
ihelp[6] = data[8] + 48

print(chr(ihelp[0]), chr(ihelp[1]), chr(ihelp[2]), chr(ihelp[3]), chr(ihelp[4]), chr(ihelp[5]), chr(ihelp[6]))



