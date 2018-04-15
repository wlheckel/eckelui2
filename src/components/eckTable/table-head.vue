<template>
    <table>
        <thead>
            <tr v-for="(cols,rowIndex) in headRows" :key="rowIndex">
                <th v-for="(column,index) in cols" :key="index"
                    :colspan="column.colSpan"
                    :rowspan="column.rowSpan"
                    :class="alignCls(column)">
                    <div>
                        
                    </div>
                </th>
            </tr>
        </thead>
    </table>
</template>

<script>
    
</script>

<style lang="less" scoped>

</style>
