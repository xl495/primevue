<template>
    <DocComponent title="Vue MultiSelect Component" header="MultiSelect" description="MultiSelect is used to select multiple items from a collection." :componentDocs="docs" />
</template>

<script setup lang="ts">
import BasicDoc from '@/doc/multiselect/BasicDoc.vue';
import ChipsDoc from '@/doc/multiselect/ChipsDoc.vue';
import ClearIconDoc from '@/doc/multiselect/ClearIconDoc.vue';
import DisabledDoc from '@/doc/multiselect/DisabledDoc.vue';
import DownloadDoc from '@/doc/multiselect/DownloadDoc.vue';
import FilledDoc from '@/doc/multiselect/FilledDoc.vue';
import FilterDoc from '@/doc/multiselect/FilterDoc.vue';
import GroupDoc from '@/doc/multiselect/GroupDoc.vue';
import ImportDoc from '@/doc/multiselect/ImportDoc.vue';
import InvalidDoc from '@/doc/multiselect/InvalidDoc.vue';
import LoadingStateDoc from '@/doc/multiselect/LoadingStateDoc.vue';
import SizesDoc from '@/doc/multiselect/SizesDoc.vue';
import TemplateDoc from '@/doc/multiselect/TemplateDoc.vue';
import VirtualScrollDoc from '@/doc/multiselect/VirtualScrollDoc.vue';

import { ref } from 'vue';

const docs = ref([
    {
        id: 'download',
        label: 'Download',
        component: DownloadDoc
    },
    {
        id: 'import',
        label: 'Import',
        component: ImportDoc
    },
    {
        id: 'basic',
        label: 'Basic',
        component: BasicDoc
    },
    {
        id: 'chips',
        label: 'Chips',
        component: ChipsDoc
    },
    {
        id: 'group',
        label: 'Group',
        component: GroupDoc
    },
    {
        id: 'template',
        label: 'Template',
        component: TemplateDoc
    },
    {
        id: 'filter',
        label: 'Filter',
        component: FilterDoc
    },
    {
        id: 'clearicon',
        label: 'Clear Icon',
        component: ClearIconDoc
    },
    {
        id: 'loadingstate',
        label: 'Loading State',
        component: LoadingStateDoc
    },
    {
        id: 'virtualscroll',
        label: 'VirtualScroll',
        component: VirtualScrollDoc
    },
    {
        id: 'filled',
        label: 'Filled',
        component: FilledDoc
    },
    {
        id: 'sizes',
        label: 'Sizes',
        component: SizesDoc
    },
    {
        id: 'invalid',
        label: 'Invalid',
        component: InvalidDoc
    },
    {
        id: 'disabled',
        label: 'Disabled',
        component: DisabledDoc
    }
]);
</script>
