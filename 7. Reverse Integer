class Solution(object):
    def reverse(self, x):
        """
        :type x: int
        :rtype: int
        """
        rez=0
        k=0
        neg=0
        if(x<0):
            x=x*(-1)
            neg=1
        while x!=0:
            rez=rez*10+(x%10)
            x=x//10
            k=k+1
            
        if rez>2147483647:      
            #2147483647 limit of int (32-bit integer)
            return 0
        if neg==0:
            return rez
        else: 
            return rez*(-1)
    

        
