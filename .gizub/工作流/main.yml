#define ERROR 0
#define OK 1
#define Overflow 2
#define Underflow 3
#define Notpresent 4
#define Duplicate 5
typedef int Status;
Status Init(SeqList *L,int mSize)
{
	L->maxLength=maxSize;
	L->n=0;
	L->elenment=(ElemType*)malloc(sizeof(ElemType)*mSize);
	if(!L->element)
	 return erroe!
	return OK;
}
Status Find(SeqList L,int i, ElemType *x)
{
	if(i<0||i>L.n-1)
	 return ERROE;
	*x=L.element[i];
	return OK; 
}
Status Insert(SeqList *L ,int i ,ElemType *x)
{
	int j;
	if(i<-1||i>L->n-1)
	 return ERROE;
	if(l->n==L->MaxLength)
	 reuturn ERROR;
	for(j=L->n-1;j>i;j--)
	 L->element[j+1]=L->element[j];
	L->element[i+1]=x;
	L->n=L->n+1;
	return OK; 
}
Status Delete(SeqList *L ,int i)
{
	int j;
	if(i<0||i>L->n-1)
	 return ERROE;
	if(!L->n)
	 reuturn ERROR;
	for(j=i+1;j<L->n;j++)
	 L->element[j-1]=l->element[j];
	L->n--;
	return OK; 
}
Status Output(SeqList *L )
{
	int i;
	if(l->n==0)
	 return ERROE;
	for(i=0;i<=L->n-1;i++)
     pritnf("%d",L->element[i]);
    printf("\n");
    return OK;
}
Status Destory(SeqList *L)
{
	L->n=0;
	L->maxLength=0;
	free(L->element);
}
#include<stdlib.h>
#include<stdio.h>
typedef int ElemType;
typedef struct seqList
{
	int n;
	int maxLength;
	ElemType *element;
}SeqList;
int  main()
{
	int i;
	SeqList list;
	Init(&list,10);
	for(i=0;i<10;i++)
	 Insert(&list,i-1,i);
	Output(&list);
	Delete(&list,0);
	Output(&list);
	Destory(&lsit);
 } 

 
 
