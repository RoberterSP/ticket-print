# ticket-print
小票打印的代码示例:

	"print_info": {
		"header_image": "",
		"header_text": "小票销售单",
		"footer_image": "",
		"footer_text": "<ul style=\"\"><li style=\"\"><i><b>&amp; &amp; &amp; 顾客须知 &amp; &amp; &amp;<\/b><\/i><\/li><li style=\"\"><i><b>1.请保留好您的购物凭证，凭此单换发票。<\/b><\/i><\/li><li style=\"\"><i><b>2.如发生退货，赠品退回。<\/b><\/i><\/li><li style=\"\"><i><b>3.退货款的付款方式与购货时的付款方式一致。<\/b><\/i><\/li><li style=\"\"><i><b>4.内衣及饰品一经售出，概不退换。<\/b><\/i><\/li><li style=\"\"><i><b>5.完全使用积分兑换的货品，如无质量问题，概不退换。<\/b><\/i><\/li><li style=\"\"><i><b>感谢惠顾，欢迎再次光临！<\/b><\/i><\/li><\/ul>"
	},
	"dataTable": {
		"barcode_image": "\/var\/mobile\/Containers\/Data\/Application\/ECBBD659-4B64-4A93-A3AE-B886D354450D\/Library\/Caches\/templateHtml\/barcode.jpg",
		"isReRecord": "否",
		"shop_name": "上海置地店(dev)",
		"mobile": "",
		"amount": "499.00",
		"member_name": "非会员",
		"total": "1",
		"type_name": "销售",
		"payments": [{
			"payment_type_name": "IC卡",
			"payment_value": "1.00"
		}, {
			"payment_type_name": "现金",
			"payment_value": "15.00"
		}, {
			"payment_type_name": "服饰代金券",
			"payment_value": "458.00"
		}, {
			"payment_type_name": "商品1",
			"payment_value": "25.00"
		}],
		"order_time": "2019-03-12 16:41:11",
		"items": [{
			"discount_rate": "100%",
			"amount": "499.00",
			"product_code": "1722042-01\/05",
			"unit_price": "499.00",
			"point": "0",
			"sale_qty": "1",
			"amount_after_discount": "499.00",
			"product_name": "夏季薄款男士修身哈伦裤-黑色\/XL"
		}],
		"order_no": "19********",
		"saleman_name": "小小",
		"isRePrint": "是"
	}
    使用方式,在小票模板的示例的初始化参数 var dataTable = {} 位置处,用以上的参数来替代,在代码的结尾部分添加 print()  即可看到小票的打印样式;
  
