# PasswordTextField
：创建一个UITextField，重点是创建一个哦，
然后用5根竖线进行分割，这样就是让我们看到了一个有6个一样的输入框在那里躺着了；
你说输入时那个黑点点啊，我们可以通过创建一个正方形的UIView，设置圆角为宽高的一半，就是一个圆了，
具体如何在中间显示，就是定义这个黑色圆点的frame啊，让他显示在中间。

可以禁止UITextField的粘贴复制功能
-(BOOL)canPerformAction:(SEL)action withSender:(id)sender {
    return NO;
}
