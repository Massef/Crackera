#!/usr/bin/python
# -*- coding: utf-8 -*-
import crypt
import hashlib

'''def sha():
    Dict = open('dico/dictionnary.txt' , 'r')
    for word in Dict.readlines():
		word = word.strip('\n')
		h = hashlib.sha1()
		h.update(word)				
		PassFile = open('pass/password.txt', 'r')
		for Pass in PassFile.readlines():
			Pass = Pass.strip('\n')
			if h.hexdigest() == Pass:
				print '[+]Password found: ' + word + ' pour le hash: ' ,h.hexdigest()'''
				
	
def md5():
    Dict = open('dico/dictionnary.txt' , 'r')
    for word in Dict.readlines():
		word = word.strip('\n')
		m = hashlib.md5()
		m.update(word)				
		PassFile = open('pass/password.txt', 'r')
		for Pass in PassFile.readlines():
			Pass = Pass.strip('\n')
			if m.hexdigest() == Pass:
				print '[+]Password found: ' + word + ' pour le hash: ' ,m.hexdigest()
						

def main():
	print '****************************************************'
	print '*********************Crackera***********************'
	print '****************************************************'
	print '*****version 0.1************************************'
	print '****************************************************'
	
	choix = raw_input(' Selectionnez le format (s)ha ou (m)d5: ')
	if choix == 's':
		sha()
	if choix == 'm':
		md5()
	
if __name__ == '__main__':
    main()
