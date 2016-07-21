# datepicker
日期编辑器
```
<link rel="stylesheet" href="lib/bootstrap-datepicker3.min.css">
<script src="lib/bootstrap-datepicker.min.js"></script>
<script src="lib/bootstrap-datepicker.zh-CN.min.js"></script>
```
```
<div class="form-group">
  <label class="control-label" for="">出生年月</label>
  <input class="form-control" type="text" name="birthday" id="datepicker">
</div>
```
```
$(function(){
    $('#datepicker').datepicker({
        format:'yyyy-mm-dd',
        language:"zh-CN",
        autoclose:true,
        todayHighlight:true
    })
})
```
