<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
	.font-hei{
	  font-family:"SimHei";
	}
	.center{
	  display: flex; 
	  align-items: center; 
	}
	.center2{
	  display: flex; 
	  align-items: center; 
	  justify-content: center;
	}
	.center9{
	  display: flex; 
	  align-items: center; 
	  justify-content:space-evenly;
	}
	.padding20{
	  padding: 20rpx; 
	  box-sizing: border-box;
	}
	.margin20{
	  margin: 20rpx 20rpx 0 20rpx;
	}
	.borderUnderline{
	  border-bottom: 1rpx solid #f2f2f2
	}
	.border{
		border-radius: 10rpx;
		border: 1rpx solid #f2f2f2;
	}
	.logo{
		border-radius: 50%;
		width: 100rpx;
		height: 100rpx;
	}
	.boxshow{
	  box-shadow: 0 0 5rpx #888888;
	}
	.CenterScreen{
	  margin:auto;
	  position:fixed;
	  left:0;
	  right:0;
	  top:0;
	  bottom:0;
	  z-index: 100;
	  background: #fff;
	  border-radius: 20rpx;
	}
	.mask{
	  width:100%;
	  height:100%;
	  position:fixed;
	  background-color:black;
	  top:0;
	  left:0;
	  opacity: 0.3;
	  z-index: 99
	}
	.text{
	  overflow:hidden; /* 超出一行文字自动隐藏 */
	  text-overflow:ellipsis; /* 文字隐藏后添加省略号 */
	  white-space:nowrap; /* 强制不换行 */
	}
	/*文本超出自动换行*/
	.text2{
		text-overflow:ellipsis;
		word-wrap:break-word
	}
	.positionBottom{ /*绝对定位到屏幕底部*/
	  position: fixed;
	  bottom: 0;
	}
</style>
