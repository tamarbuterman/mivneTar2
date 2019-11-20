# mivneTar2#pragma once
#include <iostream>
#include <list>
using namespace std;

class TrieNode
{
public:
	char key;
	list<TrieNode*> contin;
	bool isWord;
//public:
	TrieNode(char leter);
};

TrieNode::TrieNode(char leter)
{
	key = leter;
	isWord = true;
}
