<script setup>
import { ref } from 'vue';

const horizontalEvents = ref(['2022', '2023', '2024', '2025']);

const panelMenuitems = ref([
    {
        label: 'Первый курс',
        icon: 'pi pi-fw pi-table',
        items: [
            {
                label: '1 семестр',
                icon: 'pi pi-fw pi-user-plus',
                items: [
                    {
                        label: 'Линейная алгебра',
                        icon: 'pi pi-fw pi-plus',
                        command: () => openLink('https://test.com')
                    },
                    {
                        label: 'Физика',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Математический анализ',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'История',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Деловое общение',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Интерфейсы ПУ',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Английский (иностранный)',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Культурология',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Вычислительная техника',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Физкультура',
                        icon: 'pi pi-fw pi-copy'
                    }
                ]
            },
            {
                label: '2 семестр',
                icon: 'pi pi-fw pi-user-plus',
                items: [
                    {
                        label: 'Физика',
                        icon: 'pi pi-fw pi-plus',
                        command: () => openLink('https://test.com')
                    },
                    {
                        label: 'Программирование',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Микропроцессорные системы',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Математический анализ',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Философия',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Английский (иностранный)',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Дискретная математика',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Мат логика и теория алгоритмов',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Начертательная геометрия',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Физкультура',
                        icon: 'pi pi-fw pi-copy'
                    }
                ]
            },
        ]
    },
    {
        label: 'Второй курс',
        icon: 'pi pi-fw pi-shopping-cart',
        items: [
            {
                label: '3 семестр',
                icon: 'pi pi-fw pi-user-plus',
                items: [
                    {
                        label: 'Физика',
                        icon: 'pi pi-fw pi-plus',
                        command: () => openLink('https://test.com')
                    },
                    {
                        label: 'Программирование',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Мат логика и теория алгоритмов',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Английский язык (иностранный)',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Электротехника',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Дискретная математика',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Инженерная графика',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Информатика',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Диф. и интегральные уравнения',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Физкультура',
                        icon: 'pi pi-fw pi-copy'
                    }
                ]
            },
            {
                label: '4 семестр',
                icon: 'pi pi-fw pi-user-plus',
                items: [
                    {
                        label: 'Диф. и интегральные уравнения',
                        icon: 'pi pi-fw pi-plus',
                        command: () => openLink('https://test.com')
                    },
                    {
                        label: 'Иностранный язык',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Электротехника',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Физика',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Операционные системы',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Сети и телекоммуникации',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Физкультура',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Курсовая работа электротехника',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Учебная практика',
                        icon: 'pi pi-fw pi-copy'
                    }
                ]
            },
        ]
    },
    {
        label: 'Третий курс',
        icon: 'pi pi-fw pi-envelope',
        items: [
            {
                label: '5 семестр',
                icon: 'pi pi-fw pi-user-plus',
                items: [
                    {
                        label: 'Системное администрирование',
                        icon: 'pi pi-fw pi-plus',
                        command: () => openLink('https://test.com')
                    },
                    {
                        label: 'Искусственные нейронные сети',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Теория вероятностей сл. пр.',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Базы данных',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Сети и телекоммуникации',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Экономика',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Математическое моделирование',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Физкультура',
                        icon: 'pi pi-fw pi-copy'
                    }
                ]
            },
            {
                label: '6 семестр',
                icon: 'pi pi-fw pi-user-plus',
                items: [
                    {
                        label: 'Математическая статистика',
                        icon: 'pi pi-fw pi-plus',
                        command: () => openLink('https://test.com')
                    },
                    {
                        label: 'Теория графов',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Теория систем',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Компьютерные методы обработки изображений',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Кватовая теория и кв. компьютеры',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Методы оптимизации',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Управление проектами',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Физкультура',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Производственная практика',
                        icon: 'pi pi-fw pi-copy'
                    }
                ]
            },
        ]
    },
    {
        label: 'Четвертый курс',
        icon: 'pi pi-fw pi-user',
        items: [
            {
                label: '7 семестр',
                icon: 'pi pi-fw pi-user-plus',
                items: [
                    {
                        label: 'Защита информации',
                        icon: 'pi pi-fw pi-plus',
                        command: () => openLink('https://test.com')
                    },
                    {
                        label: 'Основы теории передачи информации',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Объектно-ориентированное программирование',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Безопасность жизнедеятельности',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: ' Основы права и антикоррупционного з.',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Аналитика больших объемов данных',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Графические пользовательские интерфейсы',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Обработка и анализ изображения',
                        icon: 'pi pi-fw pi-copy'
                    }
                ]
            },
            {
                label: '8 семестр',
                icon: 'pi pi-fw pi-user-plus',
                items: [
                    {
                        label: 'Средства непрерывной интеграции и непрерывной достаки приложений',
                        icon: 'pi pi-fw pi-plus',
                        command: () => openLink('https://test.com')
                    },
                    {
                        label: 'Гибкие технологии разработки программного обеспечения',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Проектирование систем телекоммуникаций',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Экспертные системы',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Программирование микроконтроллеров',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Производственная практика, преддипломная',
                        icon: 'pi pi-fw pi-copy'
                    },
                    {
                        label: 'Выполнение и защита выпускной квалификационной работы',
                        icon: 'pi pi-fw pi-copy'
                    }
                ]
            },
        ]
    }
]);

const openLink = (url) => {
  window.open(url, '_blank'); // Открывает ссылку в новой вкладке
};

const menuitems = ref([
    {
        label: 'Customers',
        items: [
            {
                label: 'New',
                icon: 'pi pi-fw pi-plus',
                command: () => downloadFile() // Добавляем обработчик события
            },
            {
                label: 'Edit',
                icon: 'pi pi-fw pi-user-edit'
            }
        ]
    },
    {
        label: 'Orders',
        items: [
            {
                label: 'View',
                icon: 'pi pi-fw pi-list'
            },
            {
                label: 'Search',
                icon: 'pi pi-fw pi-search'
            }
        ]
    }
]);

const menuitemslab = ref([
    {
        label: 'Матмоделирование',
        items: [
            {
                label: '1. вывод графика',
                icon: 'pi pi-fw pi-plus',
                command: () => downloadFile() // Добавляем обработчик события
            },
            {
                label: '2. Погрешности',
                icon: 'pi pi-fw pi-plus',
                command: () => downloadFile() // Добавляем обработчик события
            },
            {
                label: '3. Интерполяции',
                icon: 'pi pi-fw pi-plus',
                command: () => downloadFile() // Добавляем обработчик события
            },
            {
                label: '4. задание по МНК',
                icon: 'pi pi-fw pi-user-edit'
            },
            {
                label: '5. Распределения',
                icon: 'pi pi-fw pi-plus',
                command: () => downloadFile() // Добавляем обработчик события
            },
            {
                label: '6. Интегрирование',
                icon: 'pi pi-fw pi-plus',
                command: () => downloadFile() // Добавляем обработчик события
            },
            {
                label: '7. Методы решения НУ',
                icon: 'pi pi-fw pi-plus',
                command: () => downloadFile() // Добавляем обработчик события
            },
            {
                label: '8. Экстремум функции',
                icon: 'pi pi-fw pi-plus',
                command: () => downloadFile() // Добавляем обработчик события
            },
            {
                label: '9. Задание по ОДУ',
                icon: 'pi pi-fw pi-plus',
                command: () => downloadFile() // Добавляем обработчик события
            }
        ]
    }
]);

// Функция для скачивания файла
const downloadFile = () => {
    const link = document.createElement('a');
    link.href = '/filefortest'; // Замените на URL вашего файла
    link.download = 'test.txt'; // Замените на желаемое имя файла
    document.body.appendChild(link);
    link.click();
    document.body.removeChild(link);
};

const selectedCountry = ref();
const countries = ref([
    { name: 'Australia', code: 'AU' },
    { name: 'Brazil', code: 'BR' },
    { name: 'China', code: 'CN' },
    { name: 'Egypt', code: 'EG' },
    { name: 'France', code: 'FR' }
]);

const data = ref({
    key: '0',
    type: 'country',
    label: 'Argentina',
    data: 'ar',
    children: [
        {
            key: '0_0',
            type: 'country',
            label: 'Argentina',
            data: 'ar',
            children: [
                {
                    key: '0_0_0',
                    type: 'country',
                    label: 'Argentina',
                    data: 'ar'
                },
                {
                    key: '0_0_1',
                    type: 'country',
                    label: 'Croatia',
                    data: 'hr'
                }
            ]
        },
        {
            key: '0_1',
            type: 'country',
            label: 'France',
            data: 'fr',
            children: [
                {
                    key: '0_1_0',
                    type: 'country',
                    label: 'France',
                    data: 'fr'
                },
                {
                    key: '0_1_1',
                    type: 'country',
                    label: 'Morocco',
                    data: 'ma'
                }
            ]
        }
    ]
});

const messages = ref([]);
let count = ref(0);

const addMessages = () => {
    messages.value = [
        { severity: 'info', content: 'Dynamic Info Message', id: count.value++ },
        { severity: 'success', content: 'Dynamic Success Message', id: count.value++ },
        { severity: 'warn', content: 'Dynamic Warn Message', id: count.value++ }
    ];
};

const clearMessages = () => {
    messages.value = [];
};
</script>

<template>
    <div class="card">
                <div class="font-semibold text-xl mb-4">Информатика и вычислительная техника 09.03.01</div>
                <div class="font-semibold text-xl mb-4">Учебный план</div>
                <PanelMenu :model="panelMenuitems" />
    </div>
    <div class="card">
        <div class="card">
            <div class="font-semibold text-xl mb-4">Года обучения</div>
            <div class="font-semibold mb-2">Бакалавриат</div>
                <Timeline :value="horizontalEvents" layout="horizontal" align="top">
                    <template #content="slotProps">
                        {{ slotProps.item }}
                    </template>
                </Timeline>
        </div>
    </div>
    <div class ="card">
    <div class="flex flex-col md:flex-row gap-8 mt-6">
        <div class="md:w-1/3">
            <div class="card">
                <div class="font-semibold text-xl mb-4">Лекции</div>
                <div class="card flex justify-center">
                    <Listbox v-model="selectedCountry" :options="countries" optionLabel="name" class="w-full md:w-56" listStyle="max-height:250px">
                        <template #option="slotProps">
                            <div class="flex items-center">
                                <img :alt="slotProps.option.name" src="https://primefaces.org/cdn/primevue/images/flag/flag_placeholder.png" :class="`flag flag-${slotProps.option.code.toLowerCase()} mr-2`" style="width: 18px" />
                                <div>{{ slotProps.option.name }}</div>
                            </div>
                        </template>
                    </Listbox>
                </div>
            </div>
        </div>
        <div class="md:w-1/3">
            <div class="card">
                <div class="font-semibold text-xl mb-4">Теория</div>
                <Menu :model="menuitemslab" />
            </div>
        </div>
        <div class="md:w-1/3">
            <div class="card">
                <div class="font-semibold text-xl mb-4">Лабы</div>
                <Menu :model="menuitemslab" />
            </div>
        </div>
    </div>
    </div>
    <div class ="card">
    <div class="card overflow-x-auto">
        <OrganizationChart :value="data" collapsible>
            <template #country="slotProps">
                <div class="flex flex-col items-center">
                    <img :alt="slotProps.node.label" src="https://primefaces.org/cdn/primevue/images/flag/flag_placeholder.png" :class="`w-2rem flag flag-${slotProps.node.data}`" />
                    <div class="mt-4 font-medium text-lg">{{ slotProps.node.label }}</div>
                </div>
            </template>
            <template #default="slotProps">
                <span>{{slotProps.node.data.label}}</span>
            </template>
        </OrganizationChart>
    </div>
    </div>
    <div class="card flex flex-col items-center justify-center gap-4">
        <div class="flex gap-2">
            <Button label="Show" @click="addMessages()" />
            <Button label="Clear" severity="secondary" @click="clearMessages()" />
        </div>
        <transition-group name="p-message" tag="div" class="flex flex-col">
            <Message v-for="msg of messages" :key="msg.id" :severity="msg.severity" class="mt-4">{{ msg.content }}</Message>
        </transition-group>
    </div>
</template>