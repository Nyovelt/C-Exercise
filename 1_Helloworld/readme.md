### 系统必备

1. 安装 [Visual Studio Code](https://code.visualstudio.com/)。
2. 获取 [.NET Core SDK](https://dotnet.microsoft.com/download)。
3. 安装 Visual Studio Code 的 [C# 扩展](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)。 若要详细了解如何在 Visual Studio Code 上安装扩展，请访问 [VS Code 扩展市场](https://code.visualstudio.com/docs/editor/extension-gallery)。

### Hello World

让我们从 .NET Core 上的一个简单“Hello World”程序入手：

1. 打开项目：

	- 打开 Visual Studio Code。

	- 依次单击左侧菜单上的“资源管理器”图标和 **“打开文件夹”** 。

	- 从主菜单中选择“文件” > “打开文件夹”，打开要在其中放置 C# 项目的文件夹，然后单击“选择文件夹” 。 在我们的示例中，为项目创建名为“HelloWorld”的文件夹 。

		

2. 初始化 C# 项目：

	- 通过从主菜单中选择“视图” > “集成终端” ，从 Visual Studio Code 中打开集成终端。
	- 在终端窗口中，键入“`dotnet new console`”。
	- 此命令在已编写“Hello World”简单程序的文件夹中创建“Program.cs”文件，以及名为“HelloWorld.csproj”的 C# 项目文件 。
	
3. 运行“Hello World”程序：

	- 键入 `dotnet run`。