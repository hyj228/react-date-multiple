# 下载
	import  MultipleDatePicker  from  'react-date-multiple'
# 实例
![enter image description here](http://chuantu.xyz/t6/702/1562922451x2073530529.png)
# 使用方法 
	安装antd 使用antd的popover 和input输入框
		<Popover visible={popoverShow} onVisibleChange={this.handleVisibleChange} 
			content={
				<div  id="calendar_input_popover"> 
					<MultipleDatePicker onCancel={this.handleCancel} onSubmit={this.handleSubmit} /> 
				</div> 
			} placement="bottomLeft" trigger="click" >
			<Input placeholder="Basic usage" value={inputData} onClick={this.handleFocus} />
		</Popover>
