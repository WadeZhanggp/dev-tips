 


````css
	
.main{
	display: flex;
	background-color: gray;

	/*排列方式：行或者列*/
	/*flex-direction:row; */
	/*flex-direction:row-reverse;*/
	/*flex-direction:column;*/

	/*换行模式*/
	/*默认no-warp,option:warp,warp-reverse;*/
	/*flex-wrap:wrap;*/

	/*flex-flow */
	/*wrap和direction的简写*/
	flex-flow:row no-wrap;

	/*justify-content:主轴对齐方式 flex-start(默认) flex-end space-between space-around*/
	justify-content:space-around ;

	/*align-item:交叉轴对齐方式 stretch(默认) flex-start flex-end  center baseline */
	/*align-items:center;*/

	height: 1000px;
	/*align-content:换行后交叉轴对齐方式 stretch(默认) flex-start flex-end   space-between space-around*/
	/*align-content:flex-end;*/
	
	/*其他属性 
		order：排序
		flex-grow:比例
			<span style="flex-grow:1"></span>
			<span style="flex-grow:2"></span>
			<span style="flex-grow:3"></span>;
		flex-shrink:收缩;
		flex-basis:基准值;
		flex: flex-grow flex-shrink flex-basis ; 三个属性的缩写
	*/
}

.main span{	 width: 300px;   height: 100px; background-color: red; margin: 2px}
.height400{height: 400px !important;}

</style>

<div class="main">
 
	<span></span>
	<span></span>
	<span></span>
	<span></span>
	<span></span>
	<span></span>
	<span></span>
	<span></span>
	<span></span>
	<span></span>
	<span></span>
</div>
	

````

示例html

````
<div class="main">
 
	<span></span>
	<span></span>
	<span></span>
	<span></span>
	<span></span>
	<span></span>
	<span></span>
	<span></span>
	<span></span>
	<span></span>
	<span></span>
</div>
	
````