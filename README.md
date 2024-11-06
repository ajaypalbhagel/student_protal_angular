# StudentPortalAngular

Folder structure 

src/
│
├── app/
│   ├── admin/
│   │   ├── admin.module.ts
│   │   ├── admin.routing.ts
│   │   ├── components/
│   │   │   ├── manage-students/
│   │   │   │   ├── add-student/
│   │   │   │   ├── update-student/
│   │   │   │   └── list-students/
│   │   │   └── manage-teachers/
│   │   │       ├── add-teacher/
│   │   │       ├── update-teacher/
│   │   │       └── list-teachers/
│   │   └── services/
│   │       ├── admin.service.ts
│   │       └── admin.guard.ts
│   │
│   ├── student/
│   │   ├── student.module.ts
│   │   ├── student.routing.ts
│   │   ├── components/
│   │   │   ├── student-dashboard/
│   │   │   ├── view-grades/
│   │   │   └── update-profile/
│   │   └── services/
│   │       ├── student.service.ts
│   │       └── student.guard.ts
│   │
│   ├── teacher/
│   │   ├── teacher.module.ts
│   │   ├── teacher.routing.ts
│   │   ├── components/
│   │   │   ├── teacher-dashboard/
│   │   │   ├── manage-classes/
│   │   │   └── grade-students/
│   │   └── services/
│   │       ├── teacher.service.ts
│   │       └── teacher.guard.ts
│   │
│   ├── auth/
│   │   ├── auth.module.ts
│   │   ├── auth.routing.ts
│   │   ├── components/
│   │   │   ├── login/
│   │   │   ├── register/
│   │   │   └── forgot-password/
│   │   └── services/
│   │       ├── auth.service.ts
│   │       └── auth.guard.ts
│   │
│   ├── common/
│   │   ├── components/
│   │   │   ├── header/
│   │   │   ├── sidebar/
│   │   │   └── footer/
│   │   ├── directives/
│   │   ├── pipes/
│   │   └── services/
│   │       ├── notification.service.ts
│   │
│   ├── core/
│   │   ├── core.module.ts
│   │   └── interceptors/
│   │       ├── auth.interceptor.ts
│   │       └── error.interceptor.ts
│   │
│   ├── shared/
│   │   ├── models/
│   │   ├── utils/
│   │   └── constants.ts
│   │
│   ├── layouts/
│   │   ├── main-layout/
│   │   ├── auth-layout/
│   │   └── not-found-layout/
│   │
│   ├── assets/
│   │   ├── images/
│   │   └── styles/
│   │
│   ├── environments/
│   │   ├── environment.ts
│   │   └── environment.prod.ts
│   │
│   └── app.component.ts
│   └── app.module.ts
│   └── app.routing.ts
│
└── index.html
