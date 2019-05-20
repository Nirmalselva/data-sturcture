class node:
    
    def __init__(self,b):
        
        self.data=b
        self.nextt=None
class a1:
    
    def __init__(self):
        
        self.head=None
    def insert(self):
        
        val=(input("enter the no :"))
        new_node=node(val)
        new_node.nextt=self.head
        self.head=new_node
    def display(self):
        
        temp=c1.head
        while temp!=None:
           print(temp.data)
           temp=temp.nextt    

    def atend(self):
        val1=int(input())
        new_node=node(val1)
        temp=self.head
        while temp!=None:
            prev=temp
            temp=temp.nextt
        prev.nextt=new_node
        
    def atmiddle(self):
        val2=int(input())
        val3=int(input())
        new=node(val3)
        temp=self.head
        c=1
        try:
            while temp!=None:
                if c==val2:
                    break
                temp=temp.nextt
            temp1=temp.nextt
            temp.nextt=new
            new.nextt=temp1
        except:
            print("Index out of range")
    def delete(self):
        print("enter the node to delete")
        get=input()
        if self.head.data==get:
            self.head.nextt=None
            self.head=n2
            print("node deleted")
        else:
            temp=self.head
            prev=temp
            while temp.data!=get:
                prev=temp
                temp=temp.nextt
            prev.nextt=temp.nextt
            temp.nextt=None
            print("node deleted")
  
c1=a1()
ch=0
while ch!=6:
                 
                 
    print("1.insert,2.display,3.delete,4.insert_at_end,5.insert_at_middle")
    sp=int(input())
                 
    if sp==1:
        
                 
        c1.insert()
        c1.display()
    elif sp==2:
        c1.display()
        
    elif sp==3:
        c1.delete()
        c1.display()
    elif sp==4:
        c1.atend()
        c1.display()
    elif sp==5:
        c1.atmiddle()
        c1.display()
    else:    
        print("invalid ")

