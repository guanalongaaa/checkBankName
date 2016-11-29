# checkBankName


https://github.com/guanalongaaa/checkBankName.git


# <a id="如何使用"></a>如何使用


#import "BankName.h"


-(void)buttonOK{
 
    NSLog(@"按键");
//调用
    NSString *temp = [BankName BankidCardString: mytext.text];

    myLabel.text = temp;

    NSLog(@"%@",temp); 
    
}
