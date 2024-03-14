1.hook params.nativeTool.dataByAesDecryptWithBase64StringWithKeyWithIv( str, key, 'ECB'|''|null ); 实现AES ECB模式解密;

2.hook params.nativeTool.deviceIdWithTemplateWithSeparator('http',data); 实现http请求;
	提交data 为文本型
需要使用JSON.stringify(data)

{
		url:url,
		POST:true|false,
		httpParams:{
			key:value,
		},
		httpHeaders:{
			'User-Agent':''
		}
	}

	请求返回json对象 
	{
		responseHeaders:{},
		responseString:''
	}

3.hook params.nativeTool.unzipFile(); 自动识别rar文件解压缩;使用第三方库UnrarKit;

4.还没想好...
