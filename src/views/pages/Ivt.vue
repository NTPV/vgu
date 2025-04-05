<script setup>
import { ref } from 'vue';

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
</script>

<template>
    <div class="card">
                <div class="font-semibold text-xl mb-4">Информатика и вычислительная техника 09.03.01</div>
                <div class="font-semibold text-xl mb-4">Учебный план</div>
                <PanelMenu :model="panelMenuitems" />
    </div>
</template>

