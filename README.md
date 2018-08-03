# ZDTextView
自定义UITextView

自定义属性：
@property(nonatomic,copy) NSString *myPlaceholder;  //文字
@property(nonatomic,strong) UIColor *myPlaceholderColor; //文字颜色
@property  UILabel *placeholderLabel; 

//使用方法

    ZDTextView*sugesttextview=[[ZDTextView alloc]initWithFrame:CGRectMake(ScaleX(10), ScaleX(15), SIZE_WIDTH-ScaleX(20), ScaleX(240))];
    //sugesttextview.backgroundColor=[UIColor colorWithHexString:@"#efefef"];
    sugesttextview.backgroundColor=[UIColor whiteColor];
    sugesttextview.myPlaceholder=@"请输入您的建议或意见";
    sugesttextview.editable=YES;
    sugesttextview.myPlaceholderColor=[UIColor colorWithHexString:@"#999999"];
    sugesttextview.placeholderLabel.font=[UIFont systemFontOfSize:mytextfont];
    [self.view addSubview:sugesttextview];
    



