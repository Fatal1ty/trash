> [!WARNING]\
> \
> If you need to save a reference to `from_*` or `to_*` method, you should
> do it after the method is compiled. To be safe, you can always use lambda
> function:
> \
> ```python
> from_dict = lambda x: MyModel.from_dict(x)
> to_dict = lambda x: x.to_dict()
> ```


> [!WARNING]\
> No syntax highlighting anymore:
> 
> ```python\
> print("hello world")
> ```

> Syntax hilighting works if the title was removed
> ```python
> print("hello world")
> ```


**With spaces as line breaks**

> **Note**  
> This is a note

> **Note**\
> 
> This is a note

> **Warning**  
> This is a warning

> **Note**\
> This is a note

> **Warning**\
> This is a warning

> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!WARNING]
> This library is currently in pre-release stage and may have backward
> incompatible changes prior to version 1.0. Please use caution when using this
> library in production environments and be sure to thoroughly test any updates
> before upgrading to a new version.
