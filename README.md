#include "stdafx.h"
#include<iostream>

using namespace std;

class Box
{
protected:
	double H;
	double W;
	double h;
public:
	virtual void setH(double a);
	virtual double getH();
	virtual void setW(double a);
	virtual double getW();
	virtual void seth(double a);
	virtual double geth();
};


class Kashon : Box
{
public:
	void setH(double a)
	{
		H = a;
	}
	double getH()
	{
		return H;
	}
	void setW(double a)
	{
		W = a;
	}
	double getW()
	{
		return W;
	}
	void seth(double a)
	{
		h = a;
	}
	double geth()
	{
		return h;
	}
};


int main()
{

    return 0;
}
