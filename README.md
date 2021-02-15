```ts
namespace Alifilho;

Class About extends Me {
    const getCurrentWorkplace = () : Workspace => {
        return {
            company: 'Retornar',
            position: 'Front-end Developer'
        };
    }

    const getDailyKnowledge = () : string[] => {
        return [
            'TypeScript',
            'JavaScript',
            'NodeJS',
            'ReactJS',
            'ReactNative',
            'PHP',
            'Laravel'
        ];
    }

    const getFutureGoal = () => {
        return 'To contribute to better world.';
    }
}
```
