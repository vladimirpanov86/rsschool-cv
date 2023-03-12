## 1. Vladimir Panov

## 2. Contact

### - Phone: 89134563881

### - Email: vladimirpanov86@gmail.com

### - Telegram: <https://t.me/smoothsen>

## 3. About me

Constantly developing my skills in IT, really interested in being involved in finding new solutions, I am not afraid of difficulties and do my best in solving the tasks and challenges that have arisen.During this course, I want to improve my frontend skills.

## 4. Skills

HTML5/CSS, React, TypeScript, Redux, NodeJs, GIT, webpack, storybook, jest, loki.

## 5. Example of my code

```typescript
export const SideBar = memo(({ className }: SidebarProps) => {
  const [collapsed, setCollapsed] = useState(false);

  const onToggle = () => {
    setCollapsed((prev) => !prev);
  };

  const itemsList = useMemo(() => SidebarItemsList.map((item) => (
    <SidebarItem
      item={item}
      collapsed={collapsed}
      key={item.path}
    />
  )), [collapsed]);

  return (
    <div
      data-testid='sidebar'
      className={classNames(cls.SideBar, { [cls.collapsed]: collapsed }, [className])}
    >
      <Button
        data-testid='sidebar-toggle'
        onClick={onToggle}
        className={cls.collapseBtn}
        theme={ButtonTheme.BACKGROUND_INVERTED}
        size={ButtonSize.L}
        square
      >
        {collapsed ? '>' : '<'}
      </Button>
      <div className={cls.items}>
        {itemsList}
      </div>
      <div className={cls.switchers}>
        <ThemeSwitcher />
        <LangSwitcher
          short={collapsed}
          className={cls.lang}
        />
      </div>
    </div>
  );
});
```

## 6. Experience

Currently at my job I am developing an SPA using React+NodeJS+MsSQL technologies.

## 7. Education

- Offline:
Siberian State University of Telecommunications and Information Sciences
Engineer, Electronic computers, complexes, systems and networks.

- Online:
  <https://www.udemy.com/share/10208oBksZd19XRHw=/>
  <https://www.udemy.com/share/101XKiBksZd19XRHw=/>

## 8. English

Intermediate
