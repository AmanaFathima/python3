# python3
class Parent1:
    def assign_str1(self,str1):
        self.str1=str1
    def show_str1(self,str2):
        return self.str1
    
class Parent2:
    def assign_str2(self,str2):
        self.str2=str2
    def show_str2(self):
        return self.str2
    
class Child(Parent1,Parent2):
    def assign_str3(self,str3):
        self.str3=str3
    def show_str3(self):
        return self.str3
mychild=Child()
mychild.assign_str1("hello")
mychild.assign_str2("hai")
mychild.assign_str3("hey")
mychild.show_str1()
mychild.show_str2()
mychild.show_str3()
    
