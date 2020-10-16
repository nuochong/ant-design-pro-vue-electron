<template>
  <a-config-provider :locale="locale">
    <div id="app">
      <router-view />
    </div>
  </a-config-provider>
</template>

<script>
import zhCN from 'ant-design-vue/lib/locale-provider/zh_CN'
import { AppDeviceEnquire } from '@/utils/mixin'

export default {
  mixins: [AppDeviceEnquire],
  data() {
    return {
      locale: zhCN,
    }
  },
  mounted() {}
}
</script>

<style lang="less">
.ant-table-thead > tr > th {
  font-weight: bold;
}
//底部分页样式
ul.ant-pagination.ant-table-pagination {
  float: none;
  text-align: right;
  margin: 0;
  margin-top: 16px;
  li:first-child {
    float: left;
  }
}

@media (max-width: 575px) {
  ul.ant-pagination.ant-table-pagination {
    text-align: center;
    li:first-child {
      display: block;
      width: 100%;
      text-align: center;
    }
  }
}

// 全局按钮间距
.ant-btn {
  margin-right: 8px;
  margin-bottom: 12px;
}

// 时间选择器宽度调整
.date-picker {
  width: 100%;
}

// 付款单详情激活颜色
.payment-note-details-active-color {
  color: #1890ff;
}

// 操作区域标识色
.advertising-edit {
  color: #1abc9c;
}
.advertising-stick {
  color: #1890ff;
}
.advertising-delete {
  color: #f95e5a;
}

// 数据列表右上角按钮
.table-operate-add {
  float: right;
}

// 数据列表右上角操作区域按钮
// todo: 这里使用less 的嵌套无效
.content {
  .table-operate {
    button:last-child {
      margin-right: 0;
    }
    .table-operate-add {
      float: right;
    }
    :after {
      content: '';
      display: block;
      clear: both;
    }
  }
}
</style>
